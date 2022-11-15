pipeline {
          agent {
		        label {
				label '172.31.39.222'
				}
		  
		  }
		         stages {
				      stage('master') {
					              steps {
								       sh "sudo yum install httpd -y"
									   sh "sudo service httpd start"
                                       sh "sudo cd /var/www/html/"
                                        sh "sudo cp -r index.html /var/www/html/"
					sh "sudo chmod -R 777 index.html"		      
                                       } 										
					  
                             }
                         }


}
