# EC2-Module-and-Security-Group-module-and-Apache2-userdata

### Steps
1. Create a new directory for your Terraform project using a terminal: mkdir terraform-ec2.apache
   <img width="1422" height="501" alt="image" src="https://github.com/user-attachments/assets/bbf32f4d-61a9-479a-ba5e-37c8f777884d" />

2. Change into the project directory: cd terraform-ec2.apache
   <img width="1407" height="623" alt="image" src="https://github.com/user-attachments/assets/73259711-12e5-409e-bc78-b9ad1896b70e" />

3. Create directories for the EC2 and Security Group modules: mkdir -p modules/ec2 and mkdir -p modules/security_group
   <img width="1388" height="508" alt="image" src="https://github.com/user-attachments/assets/076d31b5-db11-43d8-af14-58e56a0b465c" />

4. Create EC2 module configuration
   <img width="965" height="85" alt="image" src="https://github.com/user-attachments/assets/c7251d40-5497-4c13-b6e7-b402d81eddd3" />
   <img width="1652" height="895" alt="image" src="https://github.com/user-attachments/assets/d8de2f7c-5100-452e-a9fc-095acc9e34a4" />

5. Create Security group module configuration
   <img width="934" height="108" alt="image" src="https://github.com/user-attachments/assets/41e19a9c-c12e-4b31-aec9-fd11730b4aa3" />
   <img width="1550" height="988" alt="image" src="https://github.com/user-attachments/assets/23a85cbd-a300-4fae-a4c7-069b23ba03c0" />

6. Write the user data script
   <img width="920" height="207" alt="image" src="https://github.com/user-attachments/assets/79d94b64-9c54-4b0c-a7e3-f9993384d9ee" />
   <img width="1504" height="839" alt="image" src="https://github.com/user-attachments/assets/554e6fc9-a931-4801-850f-e532296f576a" />

7. Make it executable
   <img width="1029" height="218" alt="image" src="https://github.com/user-attachments/assets/73a17ee9-5bcb-49a1-bc2e-baf9e9447576" />

8. Create a root main.tf file
   <img width="903" height="99" alt="image" src="https://github.com/user-attachments/assets/5eab665d-15c9-4ee5-a9bc-fef06731f58c" />

   <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/f7f1008f-19d8-4c2d-9d4a-7758fa942ead" />

9. Run `terraform init` and `terraform apply`
    <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/a2edefec-841e-4644-bccc-baaafc830580" />

    <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/125285e8-a944-4063-b56d-da8ca2bf266a" />

    <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/db1035dc-6489-4af4-a663-17e24db66aec" />

   10. Access the ec2 using the public ip and verify apache2 is installed
       <img width="1920" height="827" alt="image" src="https://github.com/user-attachments/assets/e66cf06d-cec5-4711-8322-948636100410" />

       <img width="1702" height="441" alt="image" src="https://github.com/user-attachments/assets/81089ba0-866c-4bc2-a874-bc58a468d8c2" />






   





   




