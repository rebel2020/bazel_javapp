load("@rules_java//java:defs.bzl", "java_binary")

java_binary(
    name = "datastore",
    srcs = ["DataStore.java"],
    main_class = "src/com/thrillio/DataStore.java",
    visibility = ["//src/com/thrillio/dao:__pkg__"],
    deps = [
        "//src/com/thrillio/constants:bookGenre",
        "//src/com/thrillio/constants:gender",
        "//src/com/thrillio/constants:movieGenre",
        "//src/com/thrillio/constants:kidFriendlyStatus",
        "//src/com/thrillio/entities:bookmark",
        "//src/com/thrillio/entities:user",
        "//src/com/thrillio/entities:userBookmark",
        "//src/com/thrillio/managers:bookmarkManager",
        "//src/com/thrillio/managers:userManager",
        "//src/com/thrillio/utils:IOUtil",
    ]
)
