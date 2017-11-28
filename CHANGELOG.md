# kzconfig changelog

## 0.3.4
### Nov 28, 2017
* Slight changes to make Context more pythonic and subclassable.
* Document the kzconfig API.


## 0.3.3
### Nov 27, 2017
* Bugfixes.


## 0.3.1
### Nov 22, 2017
* Added option `with-kubeconfig` to install-kubectl cli tool.


## 0.3.0
### Nov 21, 2017
* Full refactor, abstracted the interface to members of context which are lazy evaluated.
* Added kubectl module.
* Added install-kubectl cli command to download and install kubectl and initialize the kube-config file.


## 0.2.3
### Nov 20, 2017
* Catch AttributeError's due to missing configmaps and secrets.
* Add dnspython to required libs.


## 0.2.3
### Nov 20, 2017
* Add dnsimple to required libs.


## 0.2.2
### Nov 20, 2017
* Instantiate api's safely for added flexibility.


## 0.2.1
### Nov 16, 2017
* Added dns from simpledns.
* Added rabbit and dns credentials to context.
* Refactored sup commands into classes by module.
* util.json_dumps now has safe option.
* Using pyrkube 0.2.4 now.


## 0.2.0
* Initial commit.
