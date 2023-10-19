---
layout: page
title: Hacks Proposals
---

{::options toc_levels="2,3" /}

* TOC
{:toc}
<!-- 
## 1.Pheonix: An attempt to use light-weight NDN on smartwatch


**Project Lead:**
- Saurab Dulal

<!-- Project Members: TBD -->
**Prefered Team Size:**
- 2-4

**Targeted participant**
- People with previous NDN experience

**How does your proposal benefit NDN?**
- Attempt to use NDN on smartwatches (more detail on the proposal)

**Briefly describe the tasks**
- Check if NDN-Lite could be used, fix any potential errors and revitalize it
- Attempt to compile and install NDN-Lite on the Android OS
- Test the installation with simple examples
- If the second task fails, look for other options

**Any specific tools or language**
- C++, Android

**Expected outcomes**
- Explore the possibilities of using NDN on Android
- Compile, install, and test ndn-lite on Android OS. -->

<!-- 

## <del>2. Bug Smash – Low Hanging Fruits</del>


**Project Lead:**
- Junxiao Shi

<!-- Project Members: TBD -->
**Prefered Team Size:**
- 2-4

**Targeted participant**
- People with previous NDN experience

**How does your proposal benefit NDN?**
- improve platform software stability

**Briefly describe the tasks**

Several bugs in platform software that are easy to fix:

 - ndn-cxx may decode FreshnessPeriod as negative (#4997).
 - ndn-cxx misinterprets large dates in ValidityPeriod (#5176).
 - NFD faces/destroy should not destroy reserved faces (#4115).
 - ndncatchunks reports goodput=0 on ARMv7 (#5243).
 - NLSR hyperbolic routes have smaller cost than local apps (#5152).

Let's also get started on some new features:

 - ndn-cxx ValidatorConfig: multiple sig-type restrictions in checker (#5148).
 - NFD UDP multicast: toggle IPv4 and IPv6 independently (#4708).


**Any specific tools or language**
- C++, Boost C++ libraries

**Expected outcomes**
- Patches submitted to Gerrit for a subset of bugs, depending on actual team size and developer expertise.


 -->