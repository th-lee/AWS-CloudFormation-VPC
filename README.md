# AWS-CloudFormation-VPC
AWS CloudFormation for VPC

<br>

# Supported Region

<table>
    <tr>
        <td>Region</td>
        <td>Region Name</td>
        <td>VPC CIDR</td>
    </tr>

    <tr>
        <td>us-east-1</td>
        <td>US East (N. Virginia)</td>
        <td>10.13.0.0/16</td>
    </tr>
    
    <tr>
        <td>us-west-1</td>
        <td>US West (N. California)</td>
        <td>10.23.0.0/16</td>
    </tr>
    
    <tr>
        <td>us-west-2</td>
        <td>US West (Oregon)</td>
        <td>10.33.0.0/16</td>
    </tr>
    
    <tr>
        <td>eu-west-1</td>
        <td>EU (Ireland)</td>
        <td>10.43.0.0/16</td>
    </tr>
    
    <tr>
        <td>eu-central-1</td>
        <td>EU (Frankfurt)</td>
        <td>10.53.0.0/16</td>
    </tr>
    
    <tr>
        <td>ap-southeast-1</td>
        <td>Asia Pacific (Singapore)</td>
        <td>10.63.0.0/16</td>
    </tr>
    
    <tr>
        <td>ap-southeast-2</td>
        <td>Asia Pacific (Sydney)</td>
        <td>10.73.0.0/16</td>
    </tr>
    
    <tr>
        <td>ap-northeast-1</td>
        <td>Asia Pacific (Tokyo)</td>
        <td>10.83.0.0/16</td>
    </tr>
    
    <tr>
        <td>sa-east-1</td>
        <td>South America (Sao Paulo)</td>
        <td>10.93.0.0/16</td>
    </tr>

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
