target_sources(im_app
    PRIVATE
	  Formula.h
      Formula.cpp
	  Kb.h
      Kb.cpp
	  Parser.h
      Parser.cpp
	  SatSolver.h
      SatSolver.cpp
	  Utils.h
	  Utils.cpp
	  InconsistencyMeasureSAT.h
      InconsistencyMeasureSAT.cpp
	  ContensionEncodingSAT.cpp
	  HittingSetEncodingSAT.cpp
	  HitDistanceEncodingSAT.cpp
	  MaxDistanceEncodingSAT.cpp
	  SumDistanceEncodingSAT.cpp
	  ForgettingBasedEncodingSAT.cpp
	  InconsistencyMeasureASP.h
	  InconsistencyMeasureASP.cpp
	  ContensionASP.h
	  ContensionASP.cpp
	  ForgettingBasedASP.h
	  ForgettingBasedASP.cpp
	  HittingSetASP.h
	  HittingSetASP.cpp
	  MaxDistanceASP.h
	  MaxDistanceASP.cpp
	  SumDistanceASP.h
	  SumDistanceASP.cpp
	  HitDistanceASP.h
	  HitDistanceASP.cpp
	  Constants.h
	  LTLMeasuresASP.h
	  LTLMeasuresASP.cpp
	  InconsistencyMeasureMaxSAT.h
      InconsistencyMeasureMaxSAT.cpp
	  ContensionEncodingMaxSAT.cpp
	  MvIterativeASP.h
	  MvIterativeASP.cpp
	  ProblematicIterativeASP.h
	  ProblematicIterativeASP.cpp
	  InconsistencyMeasureNaiveSAT.h
	  InconsistencyMeasureNaiveSAT.cpp
	  ForgettingBasedNaiveSAT.h
	  ForgettingBasedNaiveSAT.cpp
      mvpMUSBased.h
      mvpMUSBased.cpp
)

target_include_directories(im_app PUBLIC ${CMAKE_CURRENT_LIST_DIR})
