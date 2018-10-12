# nginx- installation

--> update the ubuntu using the package manager 'apt'
                apt-get update 

--> install the nginx using the following command
            apt-get install nginx

--> after installation the nginx servces will e automatically fired

--> to check whether the nginx is running on your host machine or not using the following command
            ps aux | grep nginx

            #command description:-
                ps --> process
                a --> in all users
                u --> detailed information about the process
                x --> including the boot process
                | --> pipelineing the output of the process 
                grep --> it is the filter keyword which particullary filters the output as per the given keyword,
                        in this case the keyword is 'nginx'

--> to check the nginx server is now live, copy and paste the inet address of the host machine in your browser. you can find the inet     address using the following command
            
            ifconfig 

    address may look like this "167.99.93.26"

--> you can find the configuration files of the nginx server using the following command
            ls -l /etc/nginx/

--> we can build the nginx from the base in next article..
