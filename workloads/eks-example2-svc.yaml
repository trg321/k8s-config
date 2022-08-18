apiVersion: v1
kind: Service
metadata:
  name: eks-example2
  namespace: eks-example2
  labels:
    app: eks-example2
spec:
  type: LoadBalancer
  ports:
    - port: 80
      targetPort: http
      protocol: TCP
      name: http
  selector:
    app: eks-example2
