  in 25 line -> name: roboshop-admin  # User name in iam  Note :- just by maintained name k8"s will not understand this user belongs to aws iam user we need to do authentication by using this cmd - > kubectl get configmap aws-auth -n kube-system -o yaml
why we need to do all this is while creating cluster we are giving one iam user cofiguration so we are using another iam here for that purpose we need to give authorization

