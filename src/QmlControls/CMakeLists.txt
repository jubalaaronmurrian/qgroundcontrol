target_sources(${CMAKE_PROJECT_NAME}
    PRIVATE
        EditPositionDialogController.cc
        EditPositionDialogController.h
        FactValueGrid.cc
        FactValueGrid.h
        FlightPathSegment.cc
        FlightPathSegment.h
        HorizontalFactValueGrid.cc
        HorizontalFactValueGrid.h
        InstrumentValueData.cc
        InstrumentValueData.h
        MavlinkAction.cc
        MavlinkAction.h
        MavlinkActionManager.cc
        MavlinkActionManager.h
        ParameterEditorController.cc
        ParameterEditorController.h
        QGCFenceCircle.cc
        QGCFenceCircle.h
        QGCFencePolygon.cc
        QGCFencePolygon.h
        QGCFileDialogController.cc
        QGCFileDialogController.h
        QGCGeoBoundingCube.cc
        QGCGeoBoundingCube.h
        QGCImageProvider.cc
        QGCImageProvider.h
        QGCMapCircle.cc
        QGCMapCircle.h
        QGCMapPalette.cc
        QGCMapPalette.h
        QGCMapPolygon.cc
        QGCMapPolygon.h
        QGCMapPolyline.cc
        QGCMapPolyline.h
        QGCPalette.cc
        QGCPalette.h
        QGCQGeoCoordinate.cc
        QGCQGeoCoordinate.h
        QGroundControlQmlGlobal.cc
        QGroundControlQmlGlobal.h
        QmlObjectListModel.cc
        QmlObjectListModel.h
        QmlUnitsConversion.h
        RCChannelMonitorController.cc
        RCChannelMonitorController.h
        RCToParamDialogController.cc
        RCToParamDialogController.h
        ScreenToolsController.cc
        ScreenToolsController.h
        TerrainProfile.cc
        TerrainProfile.h
        ToolStripAction.cc
        ToolStripAction.h
        ToolStripActionList.cc
        ToolStripActionList.h
)

target_include_directories(${CMAKE_PROJECT_NAME} PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})

# file(GLOB_RECURSE QML_SOURCES RELATIVE ${CMAKE_CURRENT_SOURCE_DIR} ${CMAKE_CURRENT_SOURCE_DIR}/*.qml)
# qt_add_qml_module(QmlControls
#     URI QGroundControl.Controls
#     VERSION 1.0
#     QML_FILES ${QML_SOURCES}
#     RESOURCES
#       arrow-down.png
#       checkbox-check.svg
#       EditPositionDialog.FactMetaData.json
#       RCToParamDialog.FactMetaData.json
#     OUTPUT_TARGETS QmlControls_targets
#     IMPORT_PATH ${QT_QML_OUTPUT_DIRECTORY}
#     IMPORTS
#       QtQuick
#       QtQuick.Controls
#       QtQuick.Window
#       QtQuick.Dialogs
#       QtQuick.Layouts
#       Qt.labs.platform
#       QGroundControl
#       QGroundControl.Controllers
#       QGroundControl.FactControls
#       QGroundControl.Palette
#       QGroundControl.ScreenTools
#     DEPENDENCIES
#         QtCore
# )
