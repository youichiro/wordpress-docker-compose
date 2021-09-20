Steps to build a wordpress with docker-compose.

1. Git clone this repository or copy & paste docker-compose.yml in your repository.

```sh
git clone https://github.com/youichiro/wordpress-docker-compose.git
```

2. Git clone WordPress repository.

```sh
git clone https://github.com/WordPress/WordPress.git wordpress -b 5.8.1 --depth 1
```

3. docker-compose up

```sh
docker-compose up -d
```

4. Open http://localhost:8000 and setup your site configurations.

<img width="1680" alt="image" src="https://user-images.githubusercontent.com/20487308/133958761-f0389b3e-37f5-44b4-8ef5-e0fbeaff592d.png">

<img width="1679" alt="image" src="https://user-images.githubusercontent.com/20487308/133958794-e9a4adb2-5ce7-4abe-ad49-c4fa3bb3ed43.png">

5. Login and open http://localhost:8000 again.

<img width="1680" alt="スクリーンショット 2021-09-20 12 41 05" src="https://user-images.githubusercontent.com/20487308/133958773-88729f18-b078-4216-a71a-5e3466eb65d4.png">

