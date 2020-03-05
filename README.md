# AWS S3 Backup  Bucket  CloudFormation Templates
<table width="100%">
    <tr>
        <th align="left" colspan="2"><h4><a href="https://github.com/kkpkishan/aws-s3-backup-bucket-cloudformation-templates/blob/master/s3-backup-bucket-delete-previous.yml">S3 Backup Bucket</a></h4></th>
    </tr>
    <tr>
        <td width="100%" valign="top">
            <p>Create S3 Backup Bucket</p>
            <h6>Prerequisites</h6>
            <ol>
             <li>VPC</li>
             <li>VPC Endpoint</li>
            </ol>
            <h6>Create Details</h6>
            <ol>
             <li>Single S3 Bucket</li>
             <li>Enabled Versioning</li>
             <li>Enforced Encryption</li>
             <li>Creates LifeCycle to Delete Previous Versions after X Days</li>
            </ol>
            <h6>Public S3 URL</h6>
            <ol>
             <oi>https://electromech-cloudformation-templates.s3.ap-south-1.amazonaws.com/s3-backup-bucket-delete-previous.yml</li>
            </ol>
        </td>
        <td nowrap width="200" valign="top">
            <table>
                <tr>
                    <th align="left">Launch</th>
                </tr>
                <tr>
                    <td>
                        <a href="https://console.aws.amazon.com/cloudformation/home?#/stacks/new?&templateURL=https://electromech-cloudformation-templates.s3.ap-south-1.amazonaws.com/s3-backup-bucket-delete-previous.yml" target="_blank"><img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"></a>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
</table>
