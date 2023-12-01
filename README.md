# acscommonsprob
Simple project to reproduces an ACS AEM Commons build problem

Build of this project fails with

[ERROR] Failed to execute goal org.apache.maven.plugins:maven-compiler-plugin:3.1:compile (default-compile) on project acscommonsprob-reproducer: Compilation failure
[ERROR] cannot access aQute.bnd.annotation.ConsumerType
[ERROR]   class file for aQute.bnd.annotation.ConsumerType not found

Build will finish successfully when downgrading acs-aem-commons-bundle to 4.7.0 or lower.

Related Issue: https://github.com/Adobe-Consulting-Services/acs-aem-commons/issues/3223
