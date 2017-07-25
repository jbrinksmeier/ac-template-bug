# ac-template-bug
minimal example to reproduce wrong template behavior of ansible-container

`ansible-container build`

`ansible-container run`

`docker exec -it actemplatebug_test_1 cat /root/my-template.conf`

expected output: on

actual output: True
