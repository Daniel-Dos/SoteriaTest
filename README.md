# SoteriaTest
SoteriaTest - JSR 375



```
02:46:21,747 INFO  [org.jboss.modules] (main) JBoss Modules version 1.5.2.Final
02:46:22,026 INFO  [org.jboss.msc] (main) JBoss MSC version 1.2.6.Final
02:46:22,121 INFO  [org.jboss.as] (MSC service thread 1-8) WFLYSRV0049: WildFly Full 10.1.0.Final (WildFly Core 2.2.0.Final) starting
02:46:23,861 INFO  [org.jboss.as.server.deployment.scanner] (DeploymentScanner-threads - 1) WFLYDS0004: Found so.war in deployment directory. To trigger deployment create a file called so.war.dodeploy
02:46:23,863 INFO  [org.jboss.as.server.deployment.scanner] (DeploymentScanner-threads - 1) WFLYDS0004: Found oi-0.0.1-SNAPSHOT.war in deployment directory. To trigger deployment create a file called oi-0.0.1-SNAPSHOT.war.dodeploy
02:46:23,863 INFO  [org.jboss.as.server.deployment.scanner] (DeploymentScanner-threads - 1) WFLYDS0004: Found form-embedded-mvc-1.0.0-SNAPSHOT.war in deployment directory. To trigger deployment create a file called form-embedded-mvc-1.0.0-SNAPSHOT.war.dodeploy
02:46:23,863 INFO  [org.jboss.as.server.deployment.scanner] (DeploymentScanner-threads - 1) WFLYDS0004: Found SoteriaTest.war in deployment directory. To trigger deployment create a file called SoteriaTest.war.dodeploy
02:46:23,937 INFO  [org.jboss.as.server] (Controller Boot Thread) WFLYSRV0039: Creating http management service using socket-binding (management-http)
02:46:23,967 INFO  [org.xnio] (MSC service thread 1-1) XNIO version 3.4.0.Final
02:46:23,992 INFO  [org.xnio.nio] (MSC service thread 1-1) XNIO NIO Implementation Version 3.4.0.Final
02:46:24,024 INFO  [org.jboss.as.clustering.infinispan] (ServerService Thread Pool -- 41) WFLYCLINF0001: Activating Infinispan subsystem.
02:46:24,044 INFO  [org.wildfly.extension.io] (ServerService Thread Pool -- 40) WFLYIO001: Worker 'default' has auto-configured to 8 core threads with 64 task threads based on your 4 available processors
02:46:24,080 INFO  [org.wildfly.iiop.openjdk] (ServerService Thread Pool -- 42) WFLYIIOP0001: Activating IIOP Subsystem
02:46:24,108 WARN  [org.jboss.as.txn] (ServerService Thread Pool -- 60) WFLYTX0013: Node identifier property is set to the default value. Please make sure it is unique.
02:46:24,116 INFO  [org.jboss.as.connector.subsystems.datasources] (ServerService Thread Pool -- 36) WFLYJCA0004: Deploying JDBC-compliant driver class org.h2.Driver (version 1.3)
02:46:24,133 INFO  [org.jboss.as.security] (ServerService Thread Pool -- 59) WFLYSEC0002: Activating Security Subsystem
02:46:24,137 INFO  [org.jboss.as.security] (MSC service thread 1-5) WFLYSEC0001: Current PicketBox version=4.9.6.Final
02:46:24,170 INFO  [org.jboss.as.webservices] (ServerService Thread Pool -- 62) WFLYWS0002: Activating WebServices Extension
02:46:24,175 INFO  [org.jboss.as.jsf] (ServerService Thread Pool -- 48) WFLYJSF0007: Activated the following JSF Implementations: [main]
02:46:24,159 INFO  [org.jboss.as.naming] (ServerService Thread Pool -- 52) WFLYNAM0001: Activating Naming Subsystem
02:46:24,405 INFO  [org.jboss.as.connector] (MSC service thread 1-2) WFLYJCA0009: Starting JCA Subsystem (WildFly/IronJacamar 1.3.4.Final)
02:46:24,407 INFO  [org.jboss.as.connector.deployers.jdbc] (MSC service thread 1-2) WFLYJCA0018: Started Driver service with driver-name = h2
02:46:24,469 INFO  [org.jboss.as.naming] (MSC service thread 1-5) WFLYNAM0003: Starting Naming Service
02:46:24,470 INFO  [org.jboss.as.mail.extension] (MSC service thread 1-2) WFLYMAIL0001: Bound mail session [java:jboss/mail/Default]
02:46:24,515 INFO  [org.jboss.remoting] (MSC service thread 1-4) JBoss Remoting version 4.0.21.Final
02:46:24,518 INFO  [org.wildfly.extension.undertow] (MSC service thread 1-2) WFLYUT0003: Undertow 1.4.0.Final starting
02:46:24,732 INFO  [org.wildfly.extension.undertow] (ServerService Thread Pool -- 61) WFLYUT0014: Creating file handler for path '/opt/wildfly-10.1.0.Final/welcome-content' with options [directory-listing: 'false', follow-symlink: 'false', case-sensitive: 'true', safe-symlink-paths: '[]']
02:46:24,755 INFO  [org.wildfly.extension.undertow] (MSC service thread 1-8) WFLYUT0012: Started server default-server.
02:46:24,759 INFO  [org.wildfly.extension.undertow] (MSC service thread 1-1) WFLYUT0018: Host default-host starting
02:46:24,760 INFO  [org.jboss.as.ejb3] (MSC service thread 1-2) WFLYEJB0481: Strict pool slsb-strict-max-pool is using a max instance size of 64 (per class), which is derived from thread worker pool sizing.
02:46:24,760 INFO  [org.jboss.as.ejb3] (MSC service thread 1-3) WFLYEJB0482: Strict pool mdb-strict-max-pool is using a max instance size of 16 (per class), which is derived from the number of CPUs on this host.
02:46:25,004 INFO  [org.wildfly.extension.undertow] (MSC service thread 1-8) WFLYUT0006: Undertow HTTP listener default listening on 127.0.0.1:8084
02:46:25,249 INFO  [org.jboss.as.connector.subsystems.datasources] (MSC service thread 1-4) WFLYJCA0001: Bound data source [java:jboss/datasources/ExampleDS]
02:46:25,451 INFO  [org.wildfly.iiop.openjdk] (MSC service thread 1-6) WFLYIIOP0009: CORBA ORB Service started
02:46:25,530 WARN  [org.jboss.as.domain.management.security] (MSC service thread 1-8) WFLYDM0111: Keystore /opt/wildfly-10.1.0.Final/standalone/configuration/application.keystore not found, it will be auto generated on first use with a self signed certificate for host localhost
02:46:25,596 INFO  [org.jboss.as.server.deployment] (MSC service thread 1-5) WFLYSRV0027: Starting deployment of "SoteriaTest.war" (runtime-name: "SoteriaTest.war")
02:46:25,596 INFO  [org.jboss.as.server.deployment] (MSC service thread 1-4) WFLYSRV0027: Starting deployment of "ojdbc6.jar" (runtime-name: "ojdbc6.jar")
02:46:25,621 INFO  [org.jboss.as.server.deployment] (MSC service thread 1-5) WFLYSRV0027: Starting deployment of "so.war" (runtime-name: "so.war")
02:46:25,623 INFO  [org.jboss.as.server.deployment.scanner] (MSC service thread 1-2) WFLYDS0013: Started FileSystemDeploymentService for directory /opt/wildfly-10.1.0.Final/standalone/deployments
02:46:25,784 INFO  [org.apache.activemq.artemis.core.server] (ServerService Thread Pool -- 64) AMQ221000: live Message Broker is starting with configuration Broker Configuration (clustered=false,journalDirectory=/opt/wildfly-10.1.0.Final/standalone/data/activemq/journal,bindingsDirectory=/opt/wildfly-10.1.0.Final/standalone/data/activemq/bindings,largeMessagesDirectory=/opt/wildfly-10.1.0.Final/standalone/data/activemq/largemessages,pagingDirectory=/opt/wildfly-10.1.0.Final/standalone/data/activemq/paging)
02:46:25,956 INFO  [org.apache.activemq.artemis.core.server] (ServerService Thread Pool -- 64) AMQ221012: Using AIO Journal
02:46:26,122 INFO  [org.wildfly.extension.undertow] (MSC service thread 1-8) WFLYUT0006: Undertow HTTPS listener https listening on 127.0.0.1:8443
02:46:26,178 INFO  [org.infinispan.factories.GlobalComponentRegistry] (MSC service thread 1-4) ISPN000128: Infinispan version: Infinispan 'Chakra' 8.2.4.Final
02:46:26,626 INFO  [org.infinispan.configuration.cache.EvictionConfigurationBuilder] (ServerService Thread Pool -- 68) ISPN000152: Passivation configured without an eviction policy being selected. Only manually evicted entities will be passivated.
02:46:26,627 INFO  [org.infinispan.configuration.cache.EvictionConfigurationBuilder] (ServerService Thread Pool -- 70) ISPN000152: Passivation configured without an eviction policy being selected. Only manually evicted entities will be passivated.
02:46:26,628 INFO  [org.infinispan.configuration.cache.EvictionConfigurationBuilder] (ServerService Thread Pool -- 70) ISPN000152: Passivation configured without an eviction policy being selected. Only manually evicted entities will be passivated.
02:46:26,629 INFO  [org.infinispan.configuration.cache.EvictionConfigurationBuilder] (ServerService Thread Pool -- 68) ISPN000152: Passivation configured without an eviction policy being selected. Only manually evicted entities will be passivated.
02:46:26,629 INFO  [org.infinispan.configuration.cache.EvictionConfigurationBuilder] (ServerService Thread Pool -- 66) ISPN000152: Passivation configured without an eviction policy being selected. Only manually evicted entities will be passivated.
02:46:26,637 INFO  [org.infinispan.configuration.cache.EvictionConfigurationBuilder] (ServerService Thread Pool -- 66) ISPN000152: Passivation configured without an eviction policy being selected. Only manually evicted entities will be passivated.
02:46:26,714 INFO  [org.jboss.ws.common.management] (MSC service thread 1-8) JBWS022052: Starting JBossWS 5.1.5.Final (Apache CXF 3.1.6) 
02:46:26,872 INFO  [org.apache.activemq.artemis.core.server] (ServerService Thread Pool -- 64) AMQ221043: Protocol module found: [artemis-server]. Adding protocol support for: CORE
02:46:26,904 INFO  [org.apache.activemq.artemis.core.server] (ServerService Thread Pool -- 64) AMQ221043: Protocol module found: [artemis-amqp-protocol]. Adding protocol support for: AMQP
02:46:26,948 INFO  [org.apache.activemq.artemis.core.server] (ServerService Thread Pool -- 64) AMQ221043: Protocol module found: [artemis-hornetq-protocol]. Adding protocol support for: HORNETQ
02:46:26,982 INFO  [org.apache.activemq.artemis.core.server] (ServerService Thread Pool -- 64) AMQ221043: Protocol module found: [artemis-stomp-protocol]. Adding protocol support for: STOMP
02:46:27,311 INFO  [org.jboss.weld.deployer] (MSC service thread 1-3) WFLYWELD0003: Processing weld deployment SoteriaTest.war
02:46:27,312 INFO  [org.jboss.weld.deployer] (MSC service thread 1-6) WFLYWELD0003: Processing weld deployment so.war
02:46:27,421 INFO  [org.jboss.as.connector.deployers.jdbc] (MSC service thread 1-7) WFLYJCA0004: Deploying JDBC-compliant driver class oracle.jdbc.OracleDriver (version 11.2)
02:46:27,452 INFO  [org.hibernate.validator.internal.util.Version] (MSC service thread 1-6) HV000001: Hibernate Validator 5.2.4.Final
02:46:27,472 INFO  [org.jboss.as.connector.deployers.jdbc] (MSC service thread 1-7) WFLYJCA0018: Started Driver service with driver-name = ojdbc6.jar
02:46:27,489 INFO  [org.jboss.as.connector.subsystems.datasources] (MSC service thread 1-1) WFLYJCA0001: Bound data source [java:/OracleDS]
02:46:27,836 INFO  [org.jboss.weld.Version] (MSC service thread 1-5) WELD-000900: 2.3.5 (Final)
02:46:28,266 INFO  [org.wildfly.extension.messaging-activemq] (MSC service thread 1-2) WFLYMSGAMQ0016: Registered HTTP upgrade for activemq-remoting protocol handled by http-acceptor-throughput acceptor
02:46:28,266 INFO  [org.wildfly.extension.messaging-activemq] (MSC service thread 1-7) WFLYMSGAMQ0016: Registered HTTP upgrade for activemq-remoting protocol handled by http-acceptor acceptor
02:46:28,266 INFO  [org.wildfly.extension.messaging-activemq] (MSC service thread 1-3) WFLYMSGAMQ0016: Registered HTTP upgrade for activemq-remoting protocol handled by http-acceptor-throughput acceptor
02:46:28,266 INFO  [org.wildfly.extension.messaging-activemq] (MSC service thread 1-6) WFLYMSGAMQ0016: Registered HTTP upgrade for activemq-remoting protocol handled by http-acceptor acceptor
02:46:28,322 INFO  [org.apache.activemq.artemis.core.server] (ServerService Thread Pool -- 64) AMQ221007: Server is now live
02:46:28,323 INFO  [org.apache.activemq.artemis.core.server] (ServerService Thread Pool -- 64) AMQ221001: Apache ActiveMQ Artemis Message Broker version 1.1.0.wildfly-017 [nodeID=84839aa7-af84-11e6-854c-d56f8f0688f6] 
02:46:28,326 INFO  [org.apache.activemq.artemis.core.server] (ServerService Thread Pool -- 67) AMQ221003: trying to deploy queue jms.queue.DLQ
02:46:28,377 INFO  [org.wildfly.extension.messaging-activemq] (ServerService Thread Pool -- 64) WFLYMSGAMQ0002: Bound messaging object to jndi name java:jboss/exported/jms/RemoteConnectionFactory
02:46:28,378 INFO  [org.apache.activemq.artemis.core.server] (ServerService Thread Pool -- 66) AMQ221003: trying to deploy queue jms.queue.ExpiryQueue
02:46:28,379 INFO  [org.wildfly.extension.messaging-activemq] (ServerService Thread Pool -- 69) WFLYMSGAMQ0002: Bound messaging object to jndi name java:/ConnectionFactory
02:46:28,439 INFO  [org.jboss.as.connector.deployment] (MSC service thread 1-3) WFLYJCA0007: Registered connection factory java:/JmsXA
02:46:28,491 INFO  [org.apache.activemq.artemis.ra] (MSC service thread 1-3) Resource adaptor started
02:46:28,492 INFO  [org.jboss.as.connector.services.resourceadapters.ResourceAdapterActivatorService$ResourceAdapterActivator] (MSC service thread 1-3) IJ020002: Deployed: file://RaActivatoractivemq-ra
02:46:28,494 INFO  [org.jboss.as.connector.deployment] (MSC service thread 1-4) WFLYJCA0002: Bound JCA ConnectionFactory [java:/JmsXA]
02:46:28,494 INFO  [org.wildfly.extension.messaging-activemq] (MSC service thread 1-4) WFLYMSGAMQ0002: Bound messaging object to jndi name java:jboss/DefaultJMSConnectionFactory
02:46:29,782 INFO  [org.glassfish.soteria.servlet.SamRegistrationInstaller] (ServerService Thread Pool -- 66) Initializing Soteria 1.0-m04-SNAPSHOT for context '/SoteriaTest'
02:46:29,782 INFO  [org.glassfish.soteria.servlet.SamRegistrationInstaller] (ServerService Thread Pool -- 69) Initializing Soteria 1.0-m04-SNAPSHOT for context '/so'
02:46:29,914 INFO  [org.wildfly.extension.undertow] (ServerService Thread Pool -- 66) WFLYUT0021: Registered web context: /SoteriaTest
02:46:29,914 INFO  [org.wildfly.extension.undertow] (ServerService Thread Pool -- 69) WFLYUT0021: Registered web context: /so
02:46:29,965 INFO  [org.jboss.as.server] (Controller Boot Thread) WFLYSRV0010: Deployed "ojdbc6.jar" (runtime-name : "ojdbc6.jar")
02:46:29,966 INFO  [org.jboss.as.server] (ServerService Thread Pool -- 37) WFLYSRV0010: Deployed "so.war" (runtime-name : "so.war")
02:46:29,966 INFO  [org.jboss.as.server] (ServerService Thread Pool -- 37) WFLYSRV0010: Deployed "SoteriaTest.war" (runtime-name : "SoteriaTest.war")
02:46:30,126 INFO  [org.jboss.as] (Controller Boot Thread) WFLYSRV0060: Http management interface listening on http://127.0.0.1:9990/management
02:46:30,126 INFO  [org.jboss.as] (Controller Boot Thread) WFLYSRV0051: Admin console listening on http://127.0.0.1:9990
02:46:30,126 INFO  [org.jboss.as] (Controller Boot Thread) WFLYSRV0025: WildFly Full 10.1.0.Final (WildFly Core 2.2.0.Final) started in 8831ms - Started 615 of 874 services (439 services are lazy, passive or on-demand)
02:46:31,997 ERROR [org.jboss.security] (default task-2) PBOX00374: Error getting ServerAuthContext for authContextId default-host /SoteriaTest and security domain jaspitest: javax.security.auth.message.AuthException
	at org.jboss.security.auth.message.config.JBossServerAuthConfig.getAuthContext(JBossServerAuthConfig.java:187)
	at org.jboss.security.plugins.auth.JASPIServerAuthenticationManager.isValid(JASPIServerAuthenticationManager.java:99)
	at org.wildfly.extension.undertow.security.jaspi.JASPICAuthenticationMechanism.authenticate(JASPICAuthenticationMechanism.java:123)
	at io.undertow.security.impl.SecurityContextImpl$AuthAttempter.transition(SecurityContextImpl.java:245)
	at io.undertow.security.impl.SecurityContextImpl$AuthAttempter.access$100(SecurityContextImpl.java:231)
	at io.undertow.security.impl.SecurityContextImpl.attemptAuthentication(SecurityContextImpl.java:125)
	at io.undertow.security.impl.SecurityContextImpl.authTransition(SecurityContextImpl.java:99)
	at io.undertow.security.impl.SecurityContextImpl.authenticate(SecurityContextImpl.java:92)
	at io.undertow.servlet.handlers.security.ServletAuthenticationCallHandler.handleRequest(ServletAuthenticationCallHandler.java:55)
	at io.undertow.server.handlers.PredicateHandler.handleRequest(PredicateHandler.java:43)
	at io.undertow.security.handlers.AbstractConfidentialityHandler.handleRequest(AbstractConfidentialityHandler.java:46)
	at io.undertow.servlet.handlers.security.ServletConfidentialityConstraintHandler.handleRequest(ServletConfidentialityConstraintHandler.java:64)
	at io.undertow.security.handlers.AuthenticationMechanismsHandler.handleRequest(AuthenticationMechanismsHandler.java:60)
	at io.undertow.servlet.handlers.security.CachedAuthenticatedSessionHandler.handleRequest(CachedAuthenticatedSessionHandler.java:77)
	at io.undertow.security.handlers.NotificationReceiverHandler.handleRequest(NotificationReceiverHandler.java:50)
	at io.undertow.security.handlers.AbstractSecurityContextAssociationHandler.handleRequest(AbstractSecurityContextAssociationHandler.java:43)
	at io.undertow.server.handlers.PredicateHandler.handleRequest(PredicateHandler.java:43)
	at org.wildfly.extension.undertow.security.jacc.JACCContextIdHandler.handleRequest(JACCContextIdHandler.java:61)
	at io.undertow.server.handlers.PredicateHandler.handleRequest(PredicateHandler.java:43)
	at org.wildfly.extension.undertow.security.jaspi.JASPICSecureResponseHandler.handleRequest(JASPICSecureResponseHandler.java:26)
	at io.undertow.server.handlers.PredicateHandler.handleRequest(PredicateHandler.java:43)
	at io.undertow.servlet.handlers.ServletInitialHandler.handleFirstRequest(ServletInitialHandler.java:292)
	at io.undertow.servlet.handlers.ServletInitialHandler.access$100(ServletInitialHandler.java:81)
	at io.undertow.servlet.handlers.ServletInitialHandler$2.call(ServletInitialHandler.java:138)
	at io.undertow.servlet.handlers.ServletInitialHandler$2.call(ServletInitialHandler.java:135)
	at io.undertow.servlet.core.ServletRequestContextThreadSetupAction$1.call(ServletRequestContextThreadSetupAction.java:48)
	at io.undertow.servlet.core.ContextClassLoaderSetupAction$1.call(ContextClassLoaderSetupAction.java:43)
	at io.undertow.servlet.api.LegacyThreadSetupActionWrapper$1.call(LegacyThreadSetupActionWrapper.java:44)
	at io.undertow.servlet.api.LegacyThreadSetupActionWrapper$1.call(LegacyThreadSetupActionWrapper.java:44)
	at io.undertow.servlet.api.LegacyThreadSetupActionWrapper$1.call(LegacyThreadSetupActionWrapper.java:44)
	at io.undertow.servlet.api.LegacyThreadSetupActionWrapper$1.call(LegacyThreadSetupActionWrapper.java:44)
	at io.undertow.servlet.api.LegacyThreadSetupActionWrapper$1.call(LegacyThreadSetupActionWrapper.java:44)
	at io.undertow.servlet.handlers.ServletInitialHandler.dispatchRequest(ServletInitialHandler.java:272)
	at io.undertow.servlet.handlers.ServletInitialHandler.access$000(ServletInitialHandler.java:81)
	at io.undertow.servlet.handlers.ServletInitialHandler$1.handleRequest(ServletInitialHandler.java:104)
	at io.undertow.server.Connectors.executeRootHandler(Connectors.java:202)
	at io.undertow.server.HttpServerExchange$1.run(HttpServerExchange.java:805)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1142)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:617)
	at java.lang.Thread.run(Thread.java:748)
	```
