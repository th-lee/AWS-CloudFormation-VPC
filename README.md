# AWS-CloudFormation-VPC
AWS CloudFormation for VPC

<br>

# Supported Region

```
* us-east-1(10.13.0.0/16) : US East (N. Virginia)
* us-west-1(10.23.0.0/16) : US West (N. California)
* us-west-2(10.33.0.0/16) : US West (Oregon)
* eu-west-1(10.43.0.0/16) : EU (Ireland)
* eu-central-1(10.53.0.0/16) : EU (Frankfurt)
* ap-southeast-1(10.63.0.0/16) : Asia Pacific (Singapore)
* ap-southeast-2(10.73.0.0/16) : Asia Pacific (Sydney)
* ap-northeast-1(10.83.0.0/16) : Asia Pacific (Tokyo)
* sa-east-1(10.93.0.0/16) : South America (Sao Paulo) 
```

<br>

# Using Resource
+ 1 * VPC
+ 4 * Subnets : ELB / Public / Private / DB
+ 1 * Internet Gateway


<table>
    <tr>
        <td> </td> 
        <td>VPC</td>
        <td>ExELB1</td>
        <td>ExELB2</td>
        <td>Public1</td>
        <td>Public2</td>
        <td>Private1</td>
        <td>Private2</td>
        <td>Database1</td>
        <td>Database2</td>
        <td>InELB1</td>
        <td>InELB2</td>
    </tr>
    <tr>
        <td>us-east-1</td>
        <td>10.13.0.0/16</td>
        <td>10.13.111.0/24</td>
        <td>10.13.121.0/24</td>
        <td>10.13.112.0/24</td>
        <td>10.13.122.0/24</td>
        <td>10.13.213.0/24</td>
        <td>10.13.223.0/24</td>
        <td>10.13.214.0/24</td>
        <td>10.13.224.0/24</td>
        <td>10.13.215/24</td>
        <td>10.13.225/24</td>
    </tr>
</table>
