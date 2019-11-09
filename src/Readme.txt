When deactiving or removing RecordTypes you may get an error referencing a Profile you don't have access to see or change

Example - get an Error saying Platform Integration User Profile reference but don't see the profile.  Turns out the name is the Cloud Integration User Profile
https://imagineinstitute.my.salesforce.com/setup/ui/profilerecordtypeedit.jsp?id=00e6A000001Nhzn&tid=Contact&pn=System%2BAdministrator

Here is the workaround
https://help.salesforce.com/articleView?id=000325379&type=1&mode=1

Don't include the &retUrl... because that won't work (example above is the URL)