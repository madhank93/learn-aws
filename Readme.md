### Q&A

1. <details>
   <summary>What are services scopes in AWS ?</summary>

   <p>

    ![aws-global-region-az](/assets/images/aws-global-reg-az.png)

    AWS provides a lot of services and these services are either Global, Regional, or Availability Zone (AZ) specific.

   </p>
   </details>

1. <details>
   <summary>What is a IAM service and how does it works ?</summary>

   <p>

   ![iam-service](/assets/images/iam-groups-roles-policies.png)

   - **users** - refers to a single person or an application. 
   - **groups** - a set of users put under a group to apply similar policies (eg: People in Dev group will have write access and QA group will have read access for a DB)
   - **roles** - it is used to grant specific permission to specific actors (AWS service or trusted external system) for a temporary period (certain duration of time). (eg: When AWS EC2 service need access to S3 buckets)

   </p>
   </details>