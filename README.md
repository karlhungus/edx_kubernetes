# edx_kubernetes

Some objects from the edx kubernetes course
 - kubeserver v1.7.5
 - kubeclient v1.8.0
 - minikube v0.22.3

#### Notes

 - For `initial_app` you must mount the vol dir in minikube for it to get volume mounted
 - to get minikube's ip: `minikube ip`
 - For ingress to work you need `/etc/hosts` entries for like:

```
192.168.99.100 rsvp.myweb.com web.myweb.com
```
