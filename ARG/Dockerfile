ARG version
FROM almalinux:${version:-8}
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN echo "Before setting as env var - COURSE:${COURSE} , TRAINER:${TRAINER}, version:${version}version will not be available as its defined before from"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
CMD ["sleep", "100"]