RabbitMQ
=========

通过 ansible 部署在容器下运行的 RabbitMQ 服务。

Installation
------------

`ansible-galaxy install gengxiankun.rabbitmq`

Dependencies
------------

- [Docker](https://github.com/gengxiankun-galaxy/docker)

Role Variables
--------------

| parameter | description |
| --------- | ----------- |
| OPT_PATH | 服务部署目录 |
| RABBITMQ_CONTAINER_NAME | RabbitMQ 容器名称 |
| RABBITMQ_VERSION | RabbitMQ Docker 镜像版本 |
| RABBITMQ_PORT | RabbitMQ 对外端口 |
| RABBITMQ_MANAGEMENT_PORT | RabbitMQ Management 对外端口 |
| RABBITMQ_VOLUME | RabbitMQ 容器数据持久化卷标  |

Example Playbook
----------------

    - hosts: servers
      roles:
         - gengxiankun.mysql

License
-------

BSD

Author Information
------------------

This role was created in 2022 by Xiankun Geng, Learn more about the author's role in [galaxy](https://galaxy.ansible.com/gengxiankun).
