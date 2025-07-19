# Base image olaraq Ubuntu istifadə edirik
FROM ubuntu:latest

# TTY ilə bağlı bəzi problemlərin qarşısını almaq üçün bu dəyişəni əlavə edirik
ENV DEBIAN_FRONTEND=noninteractive

# Sistemi yenilə
RUN apt-get update && apt-get upgrade -y

# "Hello, World!" çap etmək üçün default command
CMD echo "Hello, World!"
