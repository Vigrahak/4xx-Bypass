# 4xxBypass
This script appears to contain various techniques aimed at bypassing 401 and 403 HTTP status codes. Specifically, it includes methods for HTTP headers fuzzing, HTTP methods/verbs fuzzing, and hop-by-hop headers fuzzing.


# Installation
 * git clone https://github.com/Vigrahak/4xxBypass
 * cd 4xxBypass
 * sudo bash ./install.sh

# Guide
Usage:    4xxbypass.sh <Domain/Path>
                                                                                                                                                                          
Example: 
 * 4xxbypass.sh example.com
 * 4xxbypass.sh http://example.com
 * 4xxbypass.sh https://example.com

Note:  If you see multiple [200 Ok]/bypasses as output, you must check the Content-Length. If the Content-Length is the same for multiple [200 Ok]/bypasses, it means a false positive. The reason can be a "301/302" redirect or a "../" payload.
                                                                                                                                              
         
