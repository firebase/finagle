scala_library(name='scala',
  dependencies=[
    pants('3rdparty:jackson-core'),
    pants('3rdparty:jackson-databind'),
    pants('3rdparty:jackson-module-scala'),
    pants('3rdparty:netty'),
    pants('3rdparty/com/twitter/common:metrics'),
    pants('finagle/finagle-core'),
    pants('finagle/finagle-http'),
    pants('util/util-core'),
  ],
  sources=rglobs('*.scala'),
  resources=[
    pants('finagle/finagle-stats/src/main/resources')
  ]
)
