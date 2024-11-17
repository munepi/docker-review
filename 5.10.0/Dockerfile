## Re:VIEW 5.10
## build main image
FROM munepi/tllangjapanese:2023 AS review-5.10.0-tl23
ENV REVIEW_VERSION=5.10.0
RUN gem install review -v=${REVIEW_VERSION} -N


FROM munepi/tllangjapanese:2022 AS review-5.10.0-tl22
ENV REVIEW_VERSION=5.10.0
RUN gem install review -v=${REVIEW_VERSION} -N
