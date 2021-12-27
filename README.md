# Fetch
Deploying EC2 using Python and Yaml configuration
-----------------------------------------------------
<h4>Prerequisites:</h4>
<ul>
  <li>Python</li>
  <li>AWS CLI with Access Key ID and Secret Access Key Credentials <a href="https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html">AWS Configuration</a></li>
  <li>An IAM user with <em>EC2FullAccess<em></li>
  <li>Boto3</li>
  <li>Python and Yaml files in the same directory</li>
</ul>
    
<h4>Setup</h4>
Run the following commands to run program<br>
    
Run AWS Configure
   >aws configure
   >
   >cat ~/.aws/configure
    
Put in your credentials in you aws folder with default region
   >[default]
   >
   >region = us-west-2
    
Next run program by
   > python3 fetchec2usingyaml.py
