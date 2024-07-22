# Create-a-Elastic-Beanstalk-and-test-manually
What is Elastic Beanstalk ?
          With Elastic Beanstalk, you can quickly deploy and manage applications in the AWS Cloud without having to learn about the infrastructure that runs those applications.
Elastic Beanstalk reduces management complexity without restricting choice or control.
          
  important note : Mostly EBS used for devlopers. Because,as a developer they do not know abount how to create correct environment in aws.Used this service they can easily create a server machine how they expect. 

1. For this project,First we create IAM role with a name of eg:beanStalk then create a  key pair and security group for ec2 machine.

   ![Alt text](imagi.1.png)
   ![Alt text](imagi.2.png)
   ![Alt text](imagi.3.png)


3. Let create a elastic beanstalk name as mywebsite

    ![Alt text](imagi.5.png)

4. In platform ,I select Node.js then I'm just choosed a sample application.

   ![Alt text](imagi.6.png)

5. Then choose a presets abount ec2 instance
   ![Alt text](imagi.7.png)

6. In configure service ,create a new role here then choosed your keypair and iam role What you created before.

   ![Alt text](imagi.8.png)

7. Choosed a vpc ,activate a public ip for your ec2 machine. Selecte a availability zone under vpc

   ![Alt text](imagi.9.png)

8. Here, choosed a your t2.micro(free tier eligible) ami id for machine

   ![Alt text](imagi.13.png)

9. In platform, software choose a proxy server. Here I choosed a nginx. It take few minute to start..

   ![Alt text](imagi.16.png)
   ![Alt text](imagi.18.png)

10. In my application, using a domain name you can launch on the server.

    ![Alt text](imagi.19.png)

11. Successfully launched a nginx server

    ![Alt text](imagi.20.png)

12. Impact of this application, Elastic ip ,Ec2 and some addition sevices should created.

    ![Alt text](imagi.21.png)
    ![Alt text](imagi.22.png)
    ![Alt text](imagi.23.png)

                                                                  
  


 



