junit_tests(name = 'scala',
  fatal_warnings = True,
  strict_deps = True,
  dependencies = [
    '3rdparty/jvm/junit',
    '3rdparty/jvm/org/scalatest',
    'util/util-logging',
    'util/util-security/src/main/scala',
    'util/util-core/src/main/scala:scala',
  ],
  sources = rglobs('*.scala'),
  resources = [
    'util/util-security/src/test/resources'
  ]
)
