## Welcome to "Hello World" with GitHub Actions

This course will walk you through writing your first action and using it with a workflow file. 

**Ready to get started? Navigate to the first issue.**

$ git commit -s -m 'This is my commit message'

FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint.sh

RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
