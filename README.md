Generate private and public RSA-256 KEY

openssl genpkey -algorithm RSA -out private_key.pem -pkeyopt rsa_keygen_bits:2048 -> PRIVATE KEY

openssl rsa -pubout -in private_key.pem -out public_key.pem -> PUBLIC KEY
