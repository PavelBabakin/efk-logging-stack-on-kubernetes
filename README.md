Ref: https://echorand.me/posts/fluentbit-kubernetes/

kubectl port-forward es-cluster-0 9200:9200 --namespace=kube-logging
kubectl port-forward kibana-866fcb5894-stpnr 5601:5601 --namespace=kube-logging
kubectl port-forward pod/webapp-74d6bb49f-b2tpb 8000:8000 --namespace=demo