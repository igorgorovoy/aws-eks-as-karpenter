# aws-eks-as-karpenter


Refs:
- Main dcocs https://karpenter.sh/docs/getting-started/ 
- EKS Workshop Karpenter https://www.eksworkshop.com/docs/autoscaling/compute/karpenter/
- Use Capacity Rebalancing in EC2 Fleet and Spot Fleet to replace at-risk Spot Instances https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-fleet-capacity-rebalance.html
- EC2 instance rebalance recommendations https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/rebalance-recommendations.html#monitor-rebalance-recommendations
- Karpenter: Amazon EKS Best Practice and Cloud Cost Optimization https://catalog.us-east-1.prod.workshops.aws/workshops/f6b4587e-b8a5-4a43-be87-26bd85a70aba/en-US
- Understand NodeClaims https://karpenter.sh/docs/concepts/nodeclaims/
- Karpenter Blueprints for Amazon EKS https://github.com/aws-samples/karpenter-blueprints
- EKS Advanced Workshop https://catalog.us-east-1.prod.workshops.aws/workshops/76a5dd80-3249-4101-8726-9be3eeee09b2/en-US/autoscaling/karpenter
- Disruption (Consolidation) https://www.eksworkshop.com/docs/autoscaling/compute/karpenter/consolidation
- Karpenter: Amazon EKS Best Practice and Cloud Cost Optimization
https://catalog.us-east-1.prod.workshops.aws/workshops/f6b4587e-b8a5-4a43-be87-26bd85a70aba/en-US/050-karpenter/ec2-spot-deployments
- Amazon EKS Best Practices Guide https://docs.aws.amazon.com/eks/latest/best-practices/karpenter.html
- Groupless Autoscaling with Karpenter - Ellis Tarn & Prateek Gogia, Amazon https://www.youtube.com/watch?v=43g8uPohTgc&ab_channel=CNCF%5BCloudNativeComputingFoundation%5D
- Scaling K8s Nodes Without Breaking the Bank or Your Sanity - Brandon Wagner & Nick Tran, Amazon https://www.youtube.com/watch?v=UBb8wbfSc34&ab_channel=CNCF%5BCloudNativeComputingFoundation%5D
- AWS re:Invent 2023 - Harness the power of Karpenter to scale, optimize & upgrade Kubernetes (CON331) https://www.youtube.com/watch?v=lkg_9ETHeks&ab_channel=AWSEvents
- Harnessing Karpenter: Transforming Kubernetes Clusters with Argo Workflows -Carlos Santana, Raj Saha https://www.youtube.com/watch?v=rq57liGu0H4&ab_channel=CNCF%5BCloudNativeComputingFoundation%5D
-  aws/karpenter-provider-aws https://github.com/aws/karpenter-provider-aws/blob/main/README.md
- Troubleshooting https://karpenter.sh/docs/troubleshooting/
- Setup Karpenter in EKS using Terraform (2024) https://www.youtube.com/watch?v=VaD-URDFZqM&ab_channel=CracktheCodewithAntman
- Anton Putra  - https://github.com/antonputra/tutorials/tree/main/lessons/114
- Kubernetes Node Autoscaling with Karpenter (AWS EKS & Terraform) https://antonputra.com/amazon/kubernetes-node-autoscaling-with-karpenter/

Tools:
- eks-node-viewer  https://github.com/awslabs/eks-node-viewer/ 