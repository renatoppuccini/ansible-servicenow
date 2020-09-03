FROM ansible/awx:14.0.0

# Rollback to root to allow the pip3 install to succeed
USER 0

RUN python3 -m ensurepip && pip3 install "pysnow"

USER 1000