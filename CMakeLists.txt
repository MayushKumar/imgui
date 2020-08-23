project(ImGui)

set(SrcFiles
  "imconfig.h"
  "imgui.cpp"
  "imgui.h"
  "imgui_internal.h"
  "imgui_widgets.cpp"
  "imgui_demo.cpp"
  "imgui_draw.cpp"
  "imstb_rectpack.h"
  "imstb_textedit.h"
  "imstb_truetype.h"
  )

add_library(ImGui
  ${SrcFiles}
  )

set_target_properties(ImGui PROPERTIES LINKER_LANGUAGE CXX)
