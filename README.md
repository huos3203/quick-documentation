# 文档

Quick 能够帮助你验证你的 Swift 和 Objective-C 程序的行为。然而，能提高你的测试技巧的不仅仅是了解如何使用 Quick。下面这些指南能够帮助你更有效地写测试 —— 不仅是和 Quick 相关的，更包括 XCTest 还有其他的测试框架。

每份指南都有一个主题。如果你对单元测试完全陌生，建议你按照从上往下的顺序阅读。

- **[在项目中添加测试](SettingUpYourXcodeProject.md)**：如果你遇到在项目中构建测试的问题，请阅读这份指南。
- **[编写高效的 XCTest 测试: Arrange，Act 和 Assert](ArrangeActAssert.md)**：阅读这份指南来了解如何更高效快速地编写 `XCTestCase` 测试。
- **[使用 Nimble 断言，让测试更清晰](NimbleAssertions.md)**
- **[用 Quick 例子和例子群组织测试](QuickExamplesAndGroups.md)**
- **[不要测试代码，而应该测试行为](BehavioralTesting.md)**：通过这份指南你能学习到哪些是好的测试，哪些是不好的测试。
- **[测试 OS X 和 iOS 应用](TestingApps.md)**：了解如何为使用 AppKit 和 UIKit 框架的代码编写测试。
- **[使用测试替身进行测试](TestUsingTestDoubles.md)**：阅读这份指南来了解什么是测试替身，以及如何使用它们。
- **[使用 Shared Assertion 来复用测试模板代码](SharedExamples.md)**：学习如何在测试中共享测试代码。
- **[配置 Quick 的行为](ConfiguringQuick.md)**：阅读这份指南来了解如何在运行测试代码时改变 Quick 的行为。
- **[在 Objective-C 中使用 Quick](QuickInObjectiveC.md)**：如果你在 Objective-C 项目使用 Quick 的过程中遇到了困难，请阅读这份指南。
- **[安装 Quick](InstallingQuick.md)**：通过这份指南了解在项目中添加 Quick 的方法：Git submodules，CocoaPods，Carthage 和 Swift Package Manager 。
- **[安装 Quick 文件模板](InstallingFileTemplates.md)**：阅读这份指南来了解如何安装文件模板以提高编写 Quick specs 的效率。
- **[更多资料](MoreResources.md)**：更多关于 OS X 和 iOS 测试的资源。
- **[常见的问题](Troubleshooting.md)**：当你遇到问题的时候，请阅读这份指南。

---
* [Build工具](issue6/issue-6-0-FangYiXiong.md)
    * [Build过程](issue6/issue-6-1-BeyondVincent.md)
    * [编译器](issue6/issue-6-2-sunsets.md)
    * [Mach-O可执行文件](issue6/issue-6-3-yishuiliunian.md)
    * [深入理解CocoaPods](issue6/issue-6-4-programmer.du.md)
    * [为iOS建立Travis CI](issue6/issue-6-5-yuan12xin.md)
---
* [调试](issue19/issue-19-0-bifidy.md)
    * [调试：案例学习](issue19/issue-19-1-weekwood.md)
    * [与调试器共舞 - LLDB的华尔兹](issue19/issue-19-2-nangege.md)
    * [调试核对清单](issue19/issue-19-3-bifidy.md)
    * [DTrace](issue19/issue-19-4-migrant.md)
    * [活动追踪](issue19/issue-19-5-dopcn.md)
---
* [测试](issue15/issue-15-0-yulingtianxia.md)
    * [行为驱动开发](issue15/issue-15-1-weekwood.md)
    * [XCTest测试实战](issue15/issue-15-2-morisunshine.md)
    * [依赖注入](issue15/issue-15-3-sunsets.md)
    * [糟糕的测试](issue15/issue-15-4-Onetaway.md)
    * [置换测试：Mock,Stub和其他](issue15/issue-15-5-ryan.md)
    * [UI测试](issue15/issue-15-6-callmewhy.md)
    * [截图测试](issue15/issue-15-7-oa414.md)
