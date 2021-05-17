# dockerautobuild from github 

FROM k8s.gcr.io/kube-controller-manager:v1.21.0
FROM k8s.gcr.io/pause:3.2
FROM quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.26.2
FROM k8s.gcr.io/kube-scheduler:v1.21.0
FROM k8s.gcr.io/kube-proxy:v1.20.6
FROM k8s.gcr.io/kube-controller-manager:v1.20.6
FROM k8s.gcr.io/kube-apiserver:v1.20.6
FROM k8s.gcr.io/etcd:3.4.9-1
FROM k8s.gcr.io/coredns:1.7.0
