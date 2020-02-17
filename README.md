# stress-testing-container

サーバーの上で負荷試験をかけるためのDockerfile

## つかいかた

```bash
git clone https://github.com/nagashima-w/stress-testing-container.git
cd stress-testing-container/tools
docker build ./ -t stress-testing
docker run -d stress-testing
```
