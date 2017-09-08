cmake_minimum_required(VERSION 2.8)
project(bcrypt)

add_library(bcrypt STATIC crypt_blowfish/crypt_blowfish.c
                          crypt_blowfish/crypt_gensalt.c
                          crypt_blowfish/wrapper.c
                          bcrypt.c)
