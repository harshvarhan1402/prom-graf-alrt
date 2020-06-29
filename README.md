############first creata namespace with name monitoring######################

kubectl create namespace monitoring


before applying grafana configs, first apply pvc.yml, it will create pvc of 10Gi, if pods get deleted, data will be saved in pvc


