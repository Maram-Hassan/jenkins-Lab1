# jenkins-Lab1
# 1-configure jenkins
![Screenshot from 2024-09-08 08-50-10](https://github.com/user-attachments/assets/345ab299-d752-4dc5-92b2-9354efcda4a8)
# 2-create viewer user
![Screenshot from 2024-09-08 09-05-31](https://github.com/user-attachments/assets/bfd708c8-843b-45c9-964a-8bf47f260742)
download role based authourization strategy 
![Screenshot from 2024-09-08 08-59-28](https://github.com/user-attachments/assets/77ce66ca-cc35-4d0f-b5ce-367e50164973)
restart jenkins after downloding the plugin then remove container and run it again
![Screenshot from 2024-09-08 09-01-20](https://github.com/user-attachments/assets/23370484-57cb-468e-a841-9a29e0ba2706)
apply role-based strategy then save
![Screenshot from 2024-09-08 09-14-45](https://github.com/user-attachments/assets/f56b9e51-293b-4dec-a570-0280ba35fffd)
add new rule
![Screenshot from 2024-09-08 09-08-41](https://github.com/user-attachments/assets/a1759ce8-5987-4051-b96a-93147879093e)
assign rule
![Screenshot from 2024-09-08 09-09-07](https://github.com/user-attachments/assets/7dcc97ae-87d1-4510-a994-c6f457809f58)
login as viewer
![Screenshot from 2024-09-08 09-11-43](https://github.com/user-attachments/assets/df702796-4a3e-48a1-a446-4f4588c9b8c2)
# 3-run pipeline:
a-clone repo
b-build dockerfile
c-push to your dockerhub account
----------------------------------------------------------------------------------------------------------------------------------------------------------
1-create pipeline
![Screenshot from 2024-09-08 12-17-07](https://github.com/user-attachments/assets/24a99add-71eb-48c1-8955-f112c21838b8)
2-create crediniatls to login to dockerhub
![Screenshot from 2024-09-09 21-57-52](https://github.com/user-attachments/assets/02461e22-e99a-4fc3-b57b-d81da6e3c794)
3-write script in the configuration of the pipeline
![Screenshot from 2024-09-09 22-00-54](https://github.com/user-attachments/assets/58d0fa63-3d26-47df-9183-a09919c9e1da)
4-then build pipeline
![Screenshot from 2024-09-09 22-12-11](https://github.com/user-attachments/assets/44d0b165-cd18-4e55-b140-f098c73b8c2e)
5-image pushed succesfully on dockerhub
![Screenshot from 2024-09-09 21-52-23](https://github.com/user-attachments/assets/e5d2f6b5-6757-4d47-a6c5-abc2af13f0e3)

