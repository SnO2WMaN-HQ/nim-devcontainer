FROM nimlang/nim:1.6.4

RUN cd /nim; nim c koch; ./koch tools; \
  ln -sf "$(pwd)/bin/nim-gdb" /bin/nim-gdb;\
  ln -sf "$(pwd)/bin/nimble" /bin/nimble;\
  ln -sf "$(pwd)/bin/nimgrep" /bin/nimgrep;\ 
  ln -sf "$(pwd)/bin/nimpretty" /bin/nimpretty;\
  ln -sf "$(pwd)/bin/nimsuggest" /bin/nimsuggest;\
  ln -sf "$(pwd)/bin/testament" /bin/testament

# RUN apt update && \
#     apt install -y \
#     gcc \
#     gcb
