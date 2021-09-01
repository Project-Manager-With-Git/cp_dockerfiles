# v0.0.1

为不同编程语言提供了不同场景的dockerfile模板:

## CXX

+ 提供grpc使用`alpine`,使用`scratch`作为基镜像以及使用upx压缩可执行文件并提供健康检查的模板

## GO

+ 提供grpc使用`debian:buster-slim`,`alpine`,`scratch`作为基镜像并使用upx压缩可执行文件并提供健康检查的模板
+ 提供http使用`debian:buster-slim`,`alpine`,`scratch`作为基镜像并使用upx压缩可执行文件并提供健康检查的模板
+ 提供通用的使用`debian:buster-slim`,`alpine`,`scratch`作为基镜像并使用upx压缩可执行文件的模板

## python

### pypy

+ 提供通用的使用`pypy:3.7-slim-buster`作为基镜像,并提供将依赖全部打包到pyz中和只打包项目代码到pyz中两种模式的模板

### python

+ 提供grpc使用的`python:slim-buster`为基镜像的模板
+ 提供http使用的`python:slim-buster`为基镜像的模板
+ 提供通用的使用`python:alpine`,`python:slim-buster`,并提供将依赖全部打包到pyz中,只打包项目代码到pyz,以及不适用pyz打包的模板