# Moondream2 docker

Dockerization of the [Hugging Face Moondream2 Space](https://huggingface.co/spaces/vikhyatk/moondream2) to make something like this

![example moondream2](example.png)

 * Model card: [vikhyatk/moondream2](https://huggingface.co/vikhyatk/moondream2)
 * Space: [vikhyatk/moondream2](https://huggingface.co/spaces/vikhyatk/moondream2)
 * Github: [moondream](https://github.com/vikhyat/moondream)

## Requisites

[Docker](https://docs.docker.com/desktop/) and [nvidia container toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) must be installed.

## Usage

### Download the image from the Docker Hub

You can download the image and run it

```bash
docker pull maximofn/moondream2:latest
./run_app.sh
```

### Build the image

Or you can build the image and run it

```bash
./build_docker_image.sh
./run_app.sh
```
