# Icinga Mail Notification 
### Problem
    Email notifications in Icinga2 for your hostgroup
    You can’t find a quick ’n dirty method
### Requirements 
    - Installation of Icinga2
    - Configured some hosts, hostgroup and services 
###  Debug if postfix not works properly 
#  Test if you can reach the mail server and 
220 Win2012-02.gin-domain.local Microsoft ESMTP MAIL Service ready at Fri, 28 Jul 2023 09:37:23 +0200
ehlo win2012-02
250-Win2012-02.gin-domain.local Hello [10.160.118.120]
250-SIZE 104857600
250-PIPELINING
250-DSN
250-ENHANCEDSTATUSCODES
250-STARTTLS
250-8BITMIME
250-BINARYMIME
250 CHUNKING
mail from: monitoring@gin.de
250 2.1.0 Sender OK
rcpt to: administrator@gin.de
250 2.1.5 Recipient OK
data
354 Start mail input; end with <CRLF>.<CRLF>
test
09:39 Uhr
.
quit
#
