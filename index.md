---

layout: col-sidebar
title: OWASP jvmxray
tags: rasp monitor securitymanager java
level: 2
type: tool
pitch: JVMXRay monitors application access to protected Java resources

---

# Welcome to JVMXRay

JVMXRay is a technology for monitoring access to system resources within the Java Virtual Machine.  It’s designed with application security emphasis but some will also find it beneficial for software quality processes and diagnostics.

```
CONSIDERATIONS:
This project is being activty under review for acceptance as an OWASP project. Please
consider this early stage code, with bugs, not suitable for production use. 
There be dragons.  You were warned!
```

## Benefits
Following is a quick list of some of the more important benefits.

### Identify protected resources
Track different types of events of interest related to sockets, files, process execution, and more.  When an event of interest occurs, process it as you wish.  At the moment, adaptors for the system console (e.g., System.out), logback, and Java Logging, are available with others in process. 

### No code changes required
JVMXRay does not require any changes to your application source code to work.  The code is pulled into the JVM by a command line option.  The solution is 100% Java code so it runs anywhere.

### Supply chain insights
An ancilary benefit of not requiring source code is that JVMXRay provides insight into your applications dependencies including 3rd party libraries (e.g. Jar files).  Events provide the source of origin where your classes where loaded when the event is generated.

### Extensible & Open
Don't see an adapter or filter that works for you and know how to code?  Roll up your sleeves and write one.  It's extensible.  Fix a bug and submit a pull requrest.  All the source code is available.

## Audience
The anticipated audience for JVMXRay is two-fold,<br/>

**Systems Administrators**
Individuals charged with system security and interested in new methods to gather security inteligence into Java applications.

**Security Developers & Architects**
Indiviudals interested in improved security intelligence about their applications.
