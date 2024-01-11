# Resmi OpenJDK 17 Debian tabanlı Docker imajını kullan
FROM openjdk:17

# Çalışma dizinini belirle
WORKDIR /opt/app

# Uygulama dosyalarını kopyala
COPY target/*.jar app.jar

# Uygulamayı çalıştır
CMD ["java", "-jar", "app.jar"]
