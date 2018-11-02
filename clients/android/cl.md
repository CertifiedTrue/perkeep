 build the perkeep/android docker image. $ run 'make env' first to build it.
	# replaced Gomobile with the latest one.
    # So on line 50, replace with:
    # RUN git reset --hard 92f3b9caf7ba8f4f9c10074225afcba0cba47a62  // https://github.com/golang/mobile/commits/master latest commit.