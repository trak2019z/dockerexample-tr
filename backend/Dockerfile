FROM openjdk:11-jdk
RUN mkdir -p /srv/auth
COPY jwt_private.der /srv/auth/jwt_private.der
COPY jwt_public.der /srv/auth/jwt_public.der
COPY auth-0.0.1-SNAPSHOT.jar /opt/auth-0.0.1-SNAPSHOT.jar
CMD ["java","-jar","/opt/auth-0.0.1-SNAPSHOT.jar"]
