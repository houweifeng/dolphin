add_library(videod3d
  BoundingBox.cpp
  BoundingBox.h
  D3DBase.cpp
  D3DBase.h
  D3DState.cpp
  D3DState.h
  DXPipeline.cpp
  DXPipeline.h
  DXShader.cpp
  DXShader.h
  DXTexture.cpp
  DXTexture.h
  main.cpp
  NativeVertexFormat.cpp
  PerfQuery.cpp
  PerfQuery.h
  Render.cpp
  Render.h
  SwapChain.cpp
  VertexManager.cpp
  VertexManager.h
  VideoBackend.h
)

target_link_libraries(videod3d
PUBLIC
  common
  videocommon
  videod3dcommon
)
