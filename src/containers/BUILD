package(default_visibility = ['//visibility:public'])

load('@io_bazel_rules_d//d:d.bzl', 'd_binary', 'd_library')

d_library(name = 'containers',
          srcs = glob([
            '*.d',
            '*/*.d',
          ]),
          imports = ['.'],
          )
