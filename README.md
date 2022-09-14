-- aws ec2,RDS 연결 --

create table test (
id bigint(20) not null auto_increment,
content varchar(255) default null,
primary key(id)
) ENGINE=InnoDB;

insert into test(content) values('테스트');

select * from test;