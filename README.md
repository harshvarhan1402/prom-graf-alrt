############first creata namespace with name monitoring######################

kubectl create namespace monitoring


before applying prometheus and grafana configs, first apply pvc.yml(they are present in both prometheus and grafana directory), it will create pvc of 10Gi, if pods get deleted, data will be saved in pvc


