This is a test of separating out graphics from the speedcontrol dashboard and extensions, so people can make their own independent bundles

Later on, it would behoove us to make the javascript a bower component or reference with a full URL to github or something.

To try this out:

```
mkdir my-nodecg-instance
cd my-nodecg-instance
nodecg setup v0.73
nodecg install charleon/nodecg-speedcontrol
nodecg install btrim/speedcontrol-graphics
cd bundles/nodecg-speedcontrol
git checkout v0.7a
cd ../..
nodecg start
```
