SET( testMeta1Utils_SRCS testMeta1Utils.cxx )
ADD_EXECUTABLE( testMeta1Utils ${testMeta1Utils_SRCS} )
TARGET_LINK_LIBRARIES( testMeta1Utils ${METAIO_NAMESPACE} ${ZLIB_LIBRARIES})
ADD_TEST(NAME testMeta1Utils COMMAND testMeta1Utils)

SET( testMeta2Object_SRCS testMeta2Object.cxx )
ADD_EXECUTABLE( testMeta2Object ${testMeta2Object_SRCS} )
TARGET_LINK_LIBRARIES( testMeta2Object ${METAIO_NAMESPACE} ${ZLIB_LIBRARIES})
ADD_TEST(NAME testMeta2Object COMMAND testMeta2Object)

SET( testMeta3Image_SRCS testMeta3Image.cxx )
ADD_EXECUTABLE( testMeta3Image ${testMeta3Image_SRCS} )
TARGET_LINK_LIBRARIES( testMeta3Image ${METAIO_NAMESPACE} ${ZLIB_LIBRARIES})
ADD_TEST(NAME testMeta3Image COMMAND testMeta3Image)

SET( testMeta4Tube_SRCS testMeta4Tube.cxx )
ADD_EXECUTABLE( testMeta4Tube ${testMeta4Tube_SRCS} )
TARGET_LINK_LIBRARIES( testMeta4Tube ${METAIO_NAMESPACE} ${ZLIB_LIBRARIES})
ADD_TEST(NAME testMeta4Tube COMMAND testMeta4Tube)

SET( testMeta5Blob_SRCS testMeta5Blob.cxx )
ADD_EXECUTABLE( testMeta5Blob ${testMeta5Blob_SRCS} )
TARGET_LINK_LIBRARIES( testMeta5Blob ${METAIO_NAMESPACE} ${ZLIB_LIBRARIES})
ADD_TEST(NAME testMeta5Blob COMMAND testMeta5Blob)

SET( testMeta6Surface_SRCS testMeta6Surface.cxx )
ADD_EXECUTABLE( testMeta6Surface ${testMeta6Surface_SRCS} )
TARGET_LINK_LIBRARIES( testMeta6Surface ${METAIO_NAMESPACE} ${ZLIB_LIBRARIES})
ADD_TEST(NAME testMeta6Surface COMMAND testMeta6Surface)

SET( testMeta7Line_SRCS testMeta7Line.cxx )
ADD_EXECUTABLE( testMeta7Line ${testMeta7Line_SRCS} )
TARGET_LINK_LIBRARIES( testMeta7Line ${METAIO_NAMESPACE} ${ZLIB_LIBRARIES})
ADD_TEST(NAME testMeta7Line COMMAND testMeta7Line)

SET( testMeta8Scene_SRCS testMeta8Scene.cxx )
ADD_EXECUTABLE( testMeta8Scene ${testMeta8Scene_SRCS} )
TARGET_LINK_LIBRARIES( testMeta8Scene ${METAIO_NAMESPACE} ${ZLIB_LIBRARIES})
ADD_TEST(NAME testMeta8Scene COMMAND testMeta8Scene)

SET( testMeta9Landmark_SRCS testMeta9Landmark.cxx )
ADD_EXECUTABLE( testMeta9Landmark ${testMeta9Landmark_SRCS} )
TARGET_LINK_LIBRARIES( testMeta9Landmark ${METAIO_NAMESPACE} ${ZLIB_LIBRARIES})
ADD_TEST(NAME testMeta9Landmark COMMAND testMeta9Landmark)

SET( testMeta10Contour_SRCS testMeta10Contour.cxx )
ADD_EXECUTABLE( testMeta10Contour ${testMeta10Contour_SRCS} )
TARGET_LINK_LIBRARIES( testMeta10Contour ${METAIO_NAMESPACE} ${ZLIB_LIBRARIES})
ADD_TEST(NAME testMeta10Contour COMMAND testMeta10Contour)

SET( testMeta11Form_SRCS testMeta11Form.cxx )
ADD_EXECUTABLE( testMeta11Form ${testMeta11Form_SRCS} )
TARGET_LINK_LIBRARIES( testMeta11Form ${METAIO_NAMESPACE} ${ZLIB_LIBRARIES})
ADD_TEST(NAME testMeta11Form COMMAND testMeta11Form)

SET( testMeta12Array_SRCS testMeta12Array.cxx )
ADD_EXECUTABLE( testMeta12Array ${testMeta12Array_SRCS} )
TARGET_LINK_LIBRARIES( testMeta12Array ${METAIO_NAMESPACE} ${ZLIB_LIBRARIES})
ADD_TEST(NAME testMeta12Array COMMAND testMeta12Array)
