# History

  Id CommandLine
  -- -----------
   1 try { . "c:\Users\12345\AppData\Local\Programs\Microsoft VS Code\resources\app\out\vs\workbench\contrib\terminal\browser\media\shellIn...  
   2 cd .\infra\  
   3 cd .\k8s\  
   4 clear  
   5 cd ..  
   6 cd ..  
   7 cd .\auth\  
   8 ls  
   9 docker build -t shubhansukr/auth  
  10 docker build -t shubhansukr/auth .  
  11 docker images  
  12 cd ..  
  13 cd .\client\  
  14 docker build -t shubhansukr/client .  
  15 cd ..  
  16 cd .\common\  
  17 ls  
  18 cd ..  
  19 cd .\expiration\  
  20 l  
  21 ls  
  22 docker build -t shubhansukr/expiration .  
  23 cd ..\nats-test\  
  24 ls  
  25 cd ..\orders\  
  26 ls  
  27 docker build -t shubhansukr/orders .  
  28 cd ..\payments\  
  29 ls  
  30 docker build -t shubhansukr/payments .  
  31 cd ..  
  32 cd .\tickets\  
  33 docker build -t shubhansukr/tickets .  
  34 clear  
  35 cd ..  
  36 docker images  
  37 docker push shubhansukr/auth  
  38 docker push shubhansukr/client  
  39 docker push shubhansukr/expiration  
  40 docker push shubhansukr/orders  
  41 docker push shubhansukr/payments  
  42 docker push shubhansukr/tickets  
  43 clear  
  44 cd .\infra\  
  45 cd .\k8s\  
  46 kubectl apply -f .  
  47 kubectl get deployments  
  48 kubectl get services  
  49 kubectl get deployments  
  50 kubectl get deployments  
  51 kubectl get deployments  
  52 clear  
  53 cd ..  
  54 cd ..  
  55 skaffold dev  
