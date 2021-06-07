cc_library(
	name = "hello_lib",
	srcs = ["hello.cc"],
	hdrs = ["hello.hh"],
)



cc_binary(
	name = "wowza",
	srcs = ["main.cc"],
	deps = [":hello_lib"],
)
