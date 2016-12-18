# SerenityDemo
* Automated Acceptance Testing using Serenity BDD framework (previously known as Thucydides)
* Sample Project Demo using Serenity, JBehave and WebDriver

### Pre-requisite
* Latest JAVA installed and Path set
* MAVEN installed and Path set
* Firefox installed

### Getting started
* git clone _repo_
* Using your preferred IDE: IntelliJ, Eclipse etc... 
   * Open the project **_SerenityDemo_** > _mySerenity_
* Ensure your maven _setting.xml_ file has the following _pluginGroups_ (go to ~/maven/conf/settings.xml)

    **_<pluginGroups><pluginGroup>net.serenity-bdd.maven.plugins</pluginGroup></pluginGroups>_**
* From command line, go to your project location _~/SerenityDemo/mySerenity_ 
* Type <code>mvn clean verify serenity:aggregate -Dmaven.test.failure.ignore=true</code>
* By default, it will launch Firefox

### Serenity Report
* To view generated report, go to target > site > serenity > index.html

![Alt text](https://github.com/giozom/SerenityDemo/blob/master/mySerenity/misc/SerenityReports.png "Serenity Report")

# Online Reference
* Find out more about **_Serenity_** here - http://thucydides.info/#/


