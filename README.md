##ProGuard rules for RxJava shipped as AAR!

Versioning principle:

Imagine RxJava has version `x.y.z` — RxJavaProGuardRules version will be `x.y.z.n` where `n` is patch version of ProGuard rules for the concrete version of RxJava!

Example: RxJava `1.2.1`, RxJavaProGuardRules `1.2.1.n`. Easy breezy.

------------

####Download

```groovy
// RxJava itself
compile 'io.reactivex:rxjava:1.2.1'

// And ProGuard rules for RxJava!
compile 'com.artemzin.rxjava:proguard-rules:1.2.1.0'
```

You can find all releases on [Maven Central](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.artemzin.rxjava%22%20AND%20a%3A%22proguard-rules%22), and here is [the file with ProGuard rules](rxjava-proguard-rules/proguard-rules.txt).

------------

Credit for the very first ProGuard rules in this library goes to [@felipecsl](https://github.com/felipecsl)!
