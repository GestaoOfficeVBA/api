FROM trestletech/plumber
LABEL maintainer="mark"

COPY [".", "./"]

# Run
EXPOSE 8080

CMD ["R", "-e", "pr <- plumber::plumb('api.R'); pr$run(host='0.0.0.0', port=8080)"]
