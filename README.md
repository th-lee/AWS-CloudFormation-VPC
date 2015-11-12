# AWS-CloudFormation-VPC
AWS CloudFormation for VPC


![VPC Architecture](VPCArchitecture.jpg)

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
</table>
<br>
<br>
<br>



# Using Resource
+ 1 * VPC
+ 5 * Subnets : ExternalELB / Public / Private / DB / InternalELB
+ 1 * Internet Gateway
+ 2 * Availability Zone(for each Region)
+ Not Included NAT

<br>
<br>
<br>


# IP Address Digit

<table>
	<tr>
		<td colspan=3 width=240>A-Class</td>
		<td colspan=3 width=240>B-Class</td>
		<td colspan=3 width=240>C-Class</td>
		<td width=80>D-Class</td>
	</tr>
	<tr>
		<td width=80>N/A</td>
		<td width=80>1(fixed)</td>
		<td width=80>0(fixed)</td>
		<td colspan=2 width=160>Region(2-digit)</td>
		<td width=80>Biz Svc</td>
		<td width=80>Pub/Pri</td>
		<td width=80>AZ</td>
		<td width=80>Subnet</td>
		<td width=80>0</td>
	<tr>
	
</table>	
	
<br><br>
### Assigning IP-Addresses (ex. us-east-1)

<table>
    <tr>
        <td> </td> 
        <td>us-east-1</td>
    </tr>
    <tr>
        <td>VPC</td>
        <td>10.13.0.0/16</td>
    </tr>
    <tr>
        <td>ExtELB1</td>
        <td>10.13.111.0/24</td>
    </tr>
    <tr>
        <td>ExtELB2</td>
	<td>10.13.121.0/24</td>
    </tr>
    <tr>
        <td>Public1</td>
	<td>10.13.112.0/24</td>
    </tr>
    <tr>
        <td>Public2</td>
	<td>10.13.122.0/24</td>
    </tr>
    <tr>
        <td>Private1</td>
	<td>10.13.213.0/24</td>
    </tr>
    <tr>
        <td>Private2</td>
	<td>10.13.223.0/24</td>
    </tr>
    <tr>
        <td>Database1</td>
	<td>10.13.214.0/24</td>
    </tr>
    <tr>
        <td>Database2</td>
	<td>10.13.224.0/24</td>
    </tr>
    <tr>
        <td>IntELB1</td>
	<td>10.13.215.0/24</td>
    </tr>
    <tr>
        <td>IntELB2</td>
	<td>10.13.225.0/24</td>
    </tr>

</table>


![myVPC](CloudFormationOutput.jpg)
