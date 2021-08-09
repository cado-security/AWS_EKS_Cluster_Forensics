```                                                                               
 _____         _         _____                      _  _           __     _      _ 
|     | ___  _| | ___   |   __| ___  ___  _ _  ___ |_|| |_  _ _   |  |   | |_  _| |
|   --|| .'|| . || . |  |__   || -_||  _|| | ||  _|| ||  _|| | |  |  |__ |  _|| . |
|_____||__,||___||___|  |_____||___||___||___||_|  |_||_|  |_  |  |_____||_|  |___|
                                                           |___|                   
                                                           
==================================================================================
==================================================================================
==================================================================================
======Cado Security Presentation - Evidence Files SANS DFIR Conference 2021=======
==================================================================================

Attached are the files associated with the Cado Security SANS Presentation "buff your
cloud game". Where James Campbell and Allan Carchrie presented the value of forensically
analysing multiple data sources when it comes to cloud investigations. This investigation
is based on a AWS Kubernetes that has been compromised, and the associated log sources
that can be made available through AWS Cloud. For the full presentation, and outline
please refer to the blog and presentation at cadosecurity.com

===================================================================================
===================================================================================

This data has been provided to the digital forensics community to provide a resource
where people can learn how to do forensics in Amazon Cloud environments, and the useful
data sources that can be captured. This is intended for training all levels from students
to active incident response experts/consultants and is not for commercial use.

====================================================================================
====================================================================================

The data sources made avaliable within the 7zip file, include,
1) cado_cloud_collector_i-06308..._20GB_1625678779.dd.gz (which is the raw forensic
AWS EKS node image collected by Cado Response. This is a raw DD file Gzipped)
2) AWS Log files
---a) kube-apiserver* (Kube api audit logs)
---b) eni-* (AWS VPC flow logs for the AWS EKS cluster)
---c) cloudtrial* - (AWS Cloud Trail Logs)
---d) Authenticator* (AWS authentication logs for AWS EKS role/cluster)
SHA256 - 2b865d36bf7295adae5545d40be389803a841808a162d603e18a92da38a6c2ed  CadoSecurity-CloudForensics-SANS_DFIR2021-Files.7z
MD5SUM - 4f486a34ad478a33f5df94dde1a3c6b3  CadoSecurity-CloudForensics-SANS_DFIR2021-Files.7z
7z files are associated with the 7zip application, other utilities like WinRAR will work to.

------------------------------------------------------------------------------------
For a full description of the data, and key events to get you started checkout the
presentation linked via the blog on cadosecurity.com
After being decompressed, all log files can be viewed either by your favourite text editor,
or be parsed into your favourite solution.

====================================================================================

Have Fun! From The Cado Security Team! @CadoSecurity

```

You can download these files from:
- https://github.com/cado-security/AWS_EKS_Cluster_Forensics/releases/download/v1.0/CadoSecurity-CloudForensics-SANS_DFIR2021-Files.7z
