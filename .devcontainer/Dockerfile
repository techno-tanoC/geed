FROM golang:1.22.2
WORKDIR /workspace

RUN <<EOF
  go install golang.org/x/tools/gopls@latest
  go install honnef.co/go/tools/cmd/staticcheck@latest
EOF
