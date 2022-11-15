pipeline {
          agent {
		        label {
				label '172.31.39.222'
				}
		  
		  }
		         stages {
				      stage('master') {
					              steps {
								       sh "yum install httpd -y"
									   sh "service httpd start"
                                       sh "cd /var/www/html/"
                                        sh "cp -r index.html /var/www/html/"
                                       } 										
					  
                             }
                         }


}
