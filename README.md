# Apache Superset Docker

Bu repo, Apache Superset'i Docker Compose kullanarak çalıştırmak için bir yapılandırma içerir.

## Başlangıç

### Gereksinimler

- Docker
- Docker Compose

### Kurulum

1. Bu depoyu klonlayın:

   ```bash
   git clone https://github.com/kullanici_adiniz/superset-docker.git
   cd superset-docker
   ```
2. Docker Compose ile başlatın:
  ```bash
  docker-compose up -d
  ```

3. Superset içine girin:

  ```bash
  docker-compose exec superset bash
  ```

4. Veritabanını başlatın ve süper kullanıcıyı oluşturun:

  ```bash
  superset db upgrade
  superset init
  ```

6. Tarayıcıda http://localhost:8088 adresine gidin.
   
