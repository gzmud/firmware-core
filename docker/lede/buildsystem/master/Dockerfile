
########################################################################
# WARNING: This is an automatically generated Dockerfile. DO NOT EDIT. #
########################################################################

FROM wlanslovenija/firmware-base

RUN ./lede/scripts/prepare master source.git 20c349f68ca108d8b20363efbf5fa698e8446009 && \
 rm -rf .git && \
 chown -R builder:builder build
