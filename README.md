## Ocaramba
<img align="left" src="/Ocaramba.Documentation/icons/Objectivity_logo_avatar.png">

**C# Framework to automate tests using Selenium WebDriver**

[![Build status](https://ci.appveyor.com/api/projects/status/p8p3bndotyknv7rk/branch/master?svg=true)](https://ci.appveyor.com/project/ObjectivityAdminsTeam/ocaramba/branch/master)
[![Build status](https://ci.appveyor.com/api/projects/status/p8p3bndotyknv7rk?svg=true)](https://ci.appveyor.com/project/ObjectivityAdminsTeam/ocaramba)
[![Coverage Status](https://img.shields.io/coveralls/github/ObjectivityLtd/Ocaramba.svg)](https://coveralls.io/github/ObjectivityLtd/Ocaramba)
[![AppVeyor tests](https://img.shields.io/appveyor/tests/ObjectivityAdminsTeam/ocaramba.svg)](https://ci.appveyor.com/project/ObjectivityAdminsTeam/ocaramba/build/tests)
[![BrowserStack Status](https://www.browserstack.com/automate/badge.svg?badge_key=TmV0eWg4WElNTVBER2M2YWZSYVc2UjFCS2tJWjV4TUEwOFFpb0FXdGZVND0tLTJqRkVubVhnQWd2NHlISkFnMlBsM0E9PQ==--f3a8ace2e27c1ddf49487dd172e969dcacef037d)](https://www.browserstack.com/automate/public-build/TmV0eWg4WElNTVBER2M2YWZSYVc2UjFCS2tJWjV4TUEwOFFpb0FXdGZVND0tLTJqRkVubVhnQWd2NHlISkFnMlBsM0E9PQ==--f3a8ace2e27c1ddf49487dd172e969dcacef037d)
[![Build Status](https://saucelabs.com/buildstatus/jraczek)](https://saucelabs.com/beta/builds/8de234710c7c46f1b5d0e9c9438e5d06)

Test Framework was designed in Objectivity to propose common way how people should create Selenium WebDriver tests.

<img align="left" src="/Ocaramba.Documentation/icons/Help.png">
Project API documentation can be found here: http://objectivityltd.github.io/Ocaramba<br /><br />

**It provides following features:**
- Ready for parallel tests execution, more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Selenium%20Parallel%20tests%20execution)
- Possibility to use MSTest, NUnit or xUNIT framework
- Specflow ready
- Written entirely in C#
- Contains example projects how to use it
- Allows to use Chrome, Firefox, Safari or Internet Explorer
- Overrides browser profile preferences, pass arguments to browsers,  installs browser extensions, loading default firefox profile, more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Override%20browser%20profile%20preferences,%20install%20browser%20extensions)
- Extends Webdriver by additional methods like JavaScriptClick, WaitForAjax, WaitForAngular, etc., more details [here](http://objectivityltd.github.io/Ocaramba/html/d51aa97e-08b5-c0b6-6987-c10545a64ebd.htm)
- Automatically waits when locating element for specified time and conditions,GetElement method instead of Selenium FindElement, more details [here](http://objectivityltd.github.io/Ocaramba/html/3c09ca99-f931-c6c9-98fc-194eff6500ff.htm)
- Page Object Pattern
- Support for [SeleniumGrid](https://github.com/SeleniumHQ/selenium/wiki/Grid2), [Cross browser parallel test execution](https://github.com/ObjectivityLtd/Ocaramba/wiki/Cross-browser-parallel-test-execution-with-SeleniumGrid-or-testing-Cloud-Providers) with [SauceLab](https://saucelabs.com/), [TestingBot](https://testingbot.com) and [Browserstack](https://www.browserstack.com/) more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Selenium-Grid-support), Advanced Browser Capabilities and Options more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Advanced-Browser-Capabilities-and-options)
- More common locators, e.g: ```"//*[@title='{0}' and @ms.title='{1}']"```, more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/More%20common%20locators)
- Several methods to interact with kendo controls, more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Interact%20with%20kendo%20controls)
- Verify - asserts without stop tests, more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Verify-asserts-without-stop-tests)
- Measures average and 90 Percentile action times, more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Performance%20measures)
- DataDriven tests from Xml, Csv and Excel files for NUnit and  Xml, Csv for MSTest with examples, more details [NUnit](https://github.com/ObjectivityLtd/Ocaramba/wiki/NUnit-DataDriven-tests-from-Xml,-CSV-and-Excel-files), [MsTest](https://github.com/ObjectivityLtd/Ocaramba/wiki/MsTest-DataDriven-tests-from-Xml-and-CSV-files)
- Possibility to take full desktop, browser screen shot or screenshot of element - Visual Testing, save page source, more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Screen-shots:-full-desktop,-selenium.-PageSource-saving)
- Logging with NLog, EventFiringWebDriver logs, more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Logging)
- Files downloading (Firefox, Chrome), more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Downloading%20files)
- Possibility to send [SQL](http://objectivityltd.github.io/Ocaramba/html/730c92c7-831a-4449-3938-16540cf259b8.htm) or [MDX](http://objectivityltd.github.io/Ocaramba/html/7de319df-06eb-1c79-8c2d-9c60aaf3ab85.htm) queries
- Possibility of debugging framework installed from nuget package, more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Debugging-Test.Automation-framework).
- AngularJS support, more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Angular-support).
- Possiblity to check for JavaScript errors from browser, more details [here](https://github.com/ObjectivityLtd/Ocaramba/wiki/Verifying-Javascript-Errors-from-browser).

For all documentation, visit the [Ocaramba Wiki](https://github.com/ObjectivityLtd/Ocaramba/wiki).

Projects examples of using Test Framework :
- Ocaramba.Tests.Angular for AngularJS
- Ocaramba.Tests.Features for Specflow
- Ocaramba.Tests.MsTest for MsTest
- Ocaramba.Tests.NUnit for NUnit
- Ocaramba.Tests.xUnit for xUnit
- Ocaramba.Tests.PageObjects for Page Object Pattern
- Ocaramba.Documentation.shfbproj for building API documentation
- Ocaramba.Tests.CloudProviderCrossBrowser for cross browser parallel test execution with BrowserStack\SauceLabs\TestingBot\SeleniumGrid
- Ocaramba.UnitTests for unit test of framework

NUnit Example Test:

```csharp
namespace Ocaramba.Tests.NUnit.Tests
{
    using global::NUnit.Framework;

    using Ocaramba.Tests.PageObjects.PageObjects.TheInternet;

    [Parallelizable(ParallelScope.Fixtures)]
    public class JavaScriptAlertsTestsNUnit : ProjectTestBase
    {
        [Test]
        public void ClickJsAlertTest()
        {
            var internetPage = new InternetPage(this.DriverContext).OpenHomePage();
            var jsAlertsPage = internetPage.GoToJavaScriptAlerts();
            jsAlertsPage.OpenJsAlert();
            jsAlertsPage.AcceptAlert();
            Assert.AreEqual("You successfuly clicked an alert", jsAlertsPage.ResultText);
        }
    }
}

```

NUnit Example Page Object:

```csharp
namespace Ocaramba.Tests.PageObjects.PageObjects.TheInternet
{
    using System;
    using System.Globalization;

    using NLog;

    using Ocaramba;
    using Ocaramba.Extensions;
    using Ocaramba.Types;
    using Ocaramba.Tests.PageObjects;

    public class InternetPage : ProjectPageBase
    {
        private static readonly Logger Logger = LogManager.GetCurrentClassLogger();

        /// <summary>
        /// Locators for elements
        /// </summary>
        private readonly ElementLocator
            linkLocator = new ElementLocator(Locator.CssSelector, "a[href='/{0}']");

        public InternetPage(DriverContext driverContext) : base(driverContext)
        {
        }

        public JavaScriptAlertsPage GoToJavaScriptAlerts()
        {
            this.Driver.GetElement(this.linkLocator.Format("javascript_alerts")).Click();
            return new JavaScriptAlertsPage(this.DriverContext);
        }
    }
}
```
		
#### Where to start?
-------------
- See [Getting started](https://github.com/ObjectivityLtd/Ocaramba/wiki/Getting%20started).

Checkout the code or get it from [nuget.org](https://www.nuget.org/packages?q=Ocaramba)
- Ocaramba [![NuGet Badge](https://buildstats.info/nuget/Ocaramba)](https://www.nuget.org/packages/Ocaramba/)

or download Visual Studio templates [here](https://ci.appveyor.com/project/ObjectivityAdminsTeam/ocaramba-templates/build/artifacts )
