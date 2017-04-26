## ProGuard rules for RxJava shipped as AAR!

### Note about RxJava 2.x

At the moment ProGuard rules for RxJava 2.x are not required, it doesn't use Reflection nor Unsafe in a ways that require ProGuard. If at some point rules for RxJava 2.x/3.x/etc will be required — this project will be updated accordingly.

See issue [#44 for more info](https://github.com/artem-zinnatullin/RxJavaProGuardRules/issues/44).

---

Versioning principle:

Imagine RxJava has version `x.y.z` — RxJavaProGuardRules version will be `x.y.z.n` where `n` is patch version of ProGuard rules for the concrete version of RxJava!

Example: RxJava `1.2.10`, RxJavaProGuardRules `1.2.10.n`. Easy breezy.

------------

#### Download

```groovy
// RxJava itself
compile 'io.reactivex:rxjava:1.2.10'

// And ProGuard rules for RxJava!
compile 'com.artemzin.rxjava:proguard-rules:1.2.10.0'
```

You can find all releases on [Maven Central](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.artemzin.rxjava%22%20AND%20a%3A%22proguard-rules%22), and here is [the file with ProGuard rules](rxjava-proguard-rules/proguard-rules.txt).

------------

Credit for the very first ProGuard rules in this library goes to [@felipecsl](https://github.com/felipecsl)!
