 # Menggunakan base image untuk PHP dan Apache
FROM php:7.4-apache

# Salin semua file dari direktori proyek ke direktori root Apache di container
COPY . /var/www/html/

# Berikan izin pada direktori jika diperlukan
RUN chown -R www-data:www-data /var/www/html

# Expose port 80 untuk akses web
EXPOSE 80
