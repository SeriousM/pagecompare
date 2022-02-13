docker run --rm --network host -v $(pwd):/work/ -w /work/ -it mcr.microsoft.com/playwright:v1.19.0-focal /bin/bash ./run_tests.sh
