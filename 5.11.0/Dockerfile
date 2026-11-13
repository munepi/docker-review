## Re:VIEW 5.11 + Pandoc 3.14 + pandoc-crossref 0.3.26b
## build main image
FROM munepi/pandoc:3.14-tl25.20261114 AS review-5.11.0-tl25
ENV REVIEW_VERSION=5.11.0
RUN apt-get update && \
        apt-get install -y --no-install-recommends \
            build-essential ruby-zip ruby-dev && \
        apt-get clean && \
        rm -rf /var/lib/apt/lists/*
RUN gem install review -v=${REVIEW_VERSION} -N
