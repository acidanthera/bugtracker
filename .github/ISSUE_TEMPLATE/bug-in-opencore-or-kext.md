---
name: Bug in OpenCore or KEXTs
about: Only OpenCore and Lilu configurations are supported.
title: ''
labels: ''
assignees: ''

---

Please stop and read this carefully. Otherwise your issue will be left **unanswered** and **closed**.

- Only the latest released versions of OpenCore, Lilu, and other KEXTs are supported.
- Bugreports involving Chameleon, Clover, Ozmozis or alike are not accepted.
- Include your your `EFI` directory with OpenCore.
- Include OpenCore DEBUG log (refer to `Target` in Configuration.pdf).
- Include Lilu DEBUG log (refer to `-liludbgall liludump=60` boot arguments in README).

Issue tracker is _not_ a support forum, and if you have installation or usage problems, try asking your questions on [InsanelyMac.com](https://www.insanelymac.com/forum/73-developers-corner/) or [AppleLife.ru](https://applelife.ru/forums/xakintosh.67/). There could also be local communities providing Acidanthera Project support in your native language.

For example, if you have an issue with AppleALC and you have not working sound, and you **cannot** offer new resources that fix the problem for you, you should go to the **support forums**. Here there are no people who create custom audio resources, or who deal with installation issues.

When to use issue tracker:
* You have new resources or patches to add but cannot make a pull request
* You have kernel panics, crashes, hangs and believe it is not a configuration issue
* You want to discuss technical or legal stuff

_If you have a kernel panic, please ensure that you have a DEBUG version of the extension and you have `-v keepsyms=1 debug=0x100` boot arguments added. On 10.13 or higher to avoid kext names scrolling over the panic log you should also set `PanicNoKextDump=YES` in OpenCore. Use `ApplePanic=YES` for write a kernel panic log to file._
