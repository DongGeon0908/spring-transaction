# 트랜잭션

> package org.springframework.transaction.support;

# 트랜잭션 관련 스프링 클래스
- TransactionManager
  + 추상화를 위한 제일 상단의 클래스
- PlatformTransactionManager
  + 트랜잭션의 begin, commit, rollback method 
- TransactionSynchronizationManager
  + 트랜잭션을 가져올 때 싱크를 맞추기 위해 쓰레드풀에 커넥션을 동기화함
- DefaultTransactionDefinition
  + 트랜잭션 관련된 옵션 값을 
