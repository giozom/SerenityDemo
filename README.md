# SerenityDemo
* Automated Acceptance Testing using Serenity BDD framework (previously known as Thucydides)
* Sample Project Demo using Serenity, JBehave and WebDriver

### Pre-requisite
* Latest JAVA installed and Path set
* MAVEN installed and Path set
* Firefox installed

### Getting started
* git clone https://github.com/giozom/SerenityDemo
* Using your preferred IDE: IntelliJ, Eclipse etc... 
   * Open the project **SerenityDemo** > **mySerenit**
* Ensure your maven _setting.xml_ file has the following _pluginGroups_ (go to ~/maven/conf/settings.xml)

    **_<pluginGroups><pluginGroup>net.serenity-bdd.maven.plugins</pluginGroup></pluginGroups>_**
* From command line, go to your project location:
  * **~/SerenityDemo/mySerenity/**
* Type <code>mvn clean verify serenity:aggregate -Dmaven.test.failure.ignore=true</code>
* By default, it will launch Firefox

### Serenity Report
* To view generated report, go to target > site > serenity > index.html

![Alt text](https://github.com/giozom/SerenityDemo/blob/master/mySerenity/misc/SerenityReports.png "Serenity Report")

# Online Reference
* Find out more about **Serenity** here - http://thucydides.info/#/


