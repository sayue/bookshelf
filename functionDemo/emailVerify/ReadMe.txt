������֤ģ�飺
 require 
 1��PHPMailer ������뵽���PHP include_path,����ο� https://github.com/Synchro/PHPMailer��

 2��Mysql ���ݱ�
CREATE TABLE IF NOT EXISTS `users` (
`id` int(11) NOT NULL auto_increment,
`status` varchar(20) NOT NULL,
`username` varchar(20) NOT NULL,
`password` varchar(20) NOT NULL,
`email` varchar(20) NOT NULL,
`activationkey` varchar(100) NOT NULL,
PRIMARY KEY (`id`),
UNIQUE KEY `username` (`username`),
UNIQUE KEY `email` (`email`),
UNIQUE KEY `activationkey` (`activationkey`)
)



	