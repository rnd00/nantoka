# なんとか

Made because:
- I need some place where I can note down stuffs, accessible from everywhere, not めんどくさい like making a blog or something
- Getting used to git commands and whatnots
- Writing them down in *markdown*
- Things written here might be dumb for my future self, but it would serve as something I could laugh out later on too

---

## [6/26] Let's play with k8s!

### thoughts:
- check internal load balancer
- how to connect different microservices inside different clusters where everything is connected with api calls?
- error logging with EFK but different cluster?
- so there has to be like webhook?
- *how to make a multi-cluster connections without going through authentication and other めんどくさい stuffs?*
- most of it was about loadbalancing in each region (less lag?)
### something interesting
- [play with robots!](https://medium.com/pollen-robotics/in-need-for-some-ai-robotics-exploration-but-no-access-to-a-physical-robot-no-problem-5c2fa47eeece)
- [reachy](https://github.com/pollen-robotics/reachy)
### error logging:
- [winston](https://www.npmjs.com/package/winston)
- [morgan](https://github.com/expressjs/morgan)
- [morgan logs to mongodb](https://github.com/expressjs/morgan/pull/44#issuecomment-62309400) *read the snippet*
- [stream.passThrough](https://stackoverflow.com/questions/19445217/is-there-a-nodejs-passthrough-stream)
- [mongoose-morgan?](https://www.npmjs.com/package/mongoose-morgan) すでにmongoose使ったらどうする？２つデータベースコネクション立てる？
### might help:
- [k8s, Nodeport / LoadBalancer](https://kubernetes.io/docs/concepts/services-networking/service/#nodeport)
- [connecting-multiple-k8s-clusters](https://learnk8s.io/bite-sized/connecting-multiple-kubernetes-clusters)
- [multicluster connectivity with submariner](https://itnext.io/kubernetes-multi-cloud-and-multi-cluster-connectivity-with-submariner-test-cockroachdb-b79662209bd7)
- [webhook on wiki](https://en.wikipedia.org/wiki/Webhook)
- [awesome-kubernetes](https://github.com/ramitsurana/awesome-kubernetes#readme)