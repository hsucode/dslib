# 3DEXPERIENCE_Forms

新增了基于达索 3DEXPERIENCE CATIA R2020x 的UI样式库

# Interface

包含了大量的文件函数
Mode                 LastWriteTime         Length Name

----                 -------------         ------ ----

#####             2021/7/30    18:24            721 AddParametersFromExcel.bas
#####            2020/11/15     0:04            864 BatchRunKP_V6_Internal.bas
#####             2021/7/30    18:24            657 ChangeObjectNameExcel.bas
#####             2021/9/12    12:14            648 ChangePartParms.bas
#####             2021/7/30    18:24           2903 ChangePrdPrtParm.bas
#####            2020/12/20    23:02           6298 DeleteBeamAllPrd.bas
#####            2020/12/20    23:02           2818 DeleteBeamFromProduct.bas
#####            2020/12/20    23:02            189 DeleteDrawingElements.bas
#####            2020/12/20    23:02           1306 DeleteObject.bas
#####            2020/12/20    23:02           4768 DeletePartTmp.bas
#####             2021/7/30    19:58           2922 EXPORT_BEAM_DATA.bas
#####             2021/7/30    18:23           2370 EXPORT_PILE_COOR.bas
#####             2021/7/30    18:23           1033 Find_ParmSet.bas
#####             2021/12/6    16:52           2086 GetDimension.bas
#####            2020/12/20    23:03           1124 GetDistance.bas
#####             2021/9/12    12:41            441 GetLineLength.bas
#####             2021/7/30    18:22           1022 KP_Run.bas
#####            2020/12/20    23:03            697 PrintParameters.bas
#####            2020/12/20    23:03            127 PrintTypeName.bas
#####             2021/9/12    19:51            251 SearchParameters.bas
#####             2021/7/30    18:21           1640 UpdateGeometricalSet.bas

#####             2021/7/28    23:17                Automation Functions
#####             2019/6/23    21:07             17 00_change.bat
#####             2019/6/23    23:26           3880 AddLouvreWithEndOffsetByCurveFro.vb
#####             2019/6/23    10:59            438 AddNewPointOnCurveSmall.vb
#####             2019/6/23    11:00            717 AddSetIfNotThere.vb
#####             2019/6/23    11:01            276 AppendStringParm.vb
#####             2019/6/23    11:01            201 BrowseForFile.vb
#####             2019/6/23    11:02            290 BrowseForFolder.vb
#####             2019/6/23    11:02            302 CanGetAngle.vb
#####             2015/11/4     9:34          23314 CATApp.vb
#####             2016/8/21    11:32           1079 CATIA_VBA_CATAPP_CLASS.vb
#####             2019/6/23    11:03            787 CheckExcelDuplicates.vb
#####             2019/6/23    11:03            255 CheckFill.vb
#####             2019/6/23    11:03            751 CheckFolders.vb
#####             2019/6/23    11:04            679 CheckInfiniteLineNormalIntersection.vb
#####             2019/6/23    11:06            341 CheckIntersection.vb
#####             2019/6/23    11:07            421 CheckIntersectionWithMoreOptions.vb
#####             2019/6/23    11:07            338 CheckLineNormal.vb
#####             2019/6/23    11:07            206 CheckProduct.vb
#####             2019/6/23    11:08            328 CheckProjection.vb
#####             2019/6/23    11:08            378 CheckProjectionByDirection.vb
#####             2019/6/23    11:09            662 CleanOGS.vb
#####             2019/6/23    11:10            811 ClosestPoints.vb
#####             2019/6/23    11:10            235 Color_to_RGB.vb
#####             2019/6/23    11:10            687 CrossProduct.vb
#####             2019/6/23    11:11            259 CrvCheck.vb
#####             2019/6/23    11:11            367 CutObjectAndPaste.vb
#####             2019/6/23    11:11            113 deg_to_rad.vb
#####             2019/6/23    11:12            207 DeleteHSObjectsArray.vb
#####             2019/6/23    11:12            348 DeleteNonSurface (from Array).vb
#####             2019/6/23    11:14            512 DeleteNonSurfaces (from Geom Set).vb
#####             2019/6/23    11:14            281 DistanceFromEquationOfLine.vb
#####             2019/6/23    11:14            974 DoArcWallsIntersect.vb
#####             2019/6/23    11:14            106 DotProduct.vb
#####             2019/6/23    11:15            823 EmailNotify.vb
#####             2019/6/23    11:15            409 ExistsInArray.vb
#####             2019/6/23    11:16            475 ExportPtCoordToXLS.vb
#####             2021/11/6    13:21            264 ExportToPDF.vb
#####             2019/6/23    11:16            444 FilletCheck.vb
#####             2019/6/23    11:16           1946 FilletStabilizer.vb
#####             2019/6/23    11:17            623 FindClosestObjectInGeomSet.vb
#####             2019/6/23    11:17            287 FixInstanceFactory.vb
#####             2019/6/23    11:17            194 FolderVerify.vb
#####             2019/6/23    11:18            715 ForceColorArray.vb
#####             2019/6/23    11:18            839 ForceColorArrayUgly.vb
#####             2019/6/23    11:18            771 ForceColorObjUgly.vb
#####             2019/6/23    11:19            872 FurthestPoints.vb
#####             2019/6/23    11:19            578 GenerateCATPartFromProduct.vb
#####             2019/6/23    11:19            365 GenerateLengthParametersFromDblArray.vb
#####             2019/6/23    11:20            867 GeneratePublication.vb
#####             2019/6/23    11:20            323 GenerateRealParametersFromDblArray.vb
#####             2019/6/23    11:21            292 GetAcuteAngle.vb
#####             2019/6/23    11:21            740 GetAngleBetween.vb
#####             2019/6/23    11:21            726 GetCOGFromArray.vb
#####             2021/11/6    13:26            243 GetContainingPart.vb
#####             2019/6/23    11:22            420 GetFirstInstanceInExcel.vb
#####             2019/6/23    11:22           1425 GetMaxProjDistance.vb
#####             2019/6/23    11:23            561 GetMinimumDistanceAtLineEndPts.vb
#####             2019/6/23    11:23            328 GetPartFromName.vb
#####             2019/6/23    11:23            135 GetSlope.vb
#####             2019/6/23    11:24           2710 GetTechnologicalObject Parameters.vb
#####             2019/6/23    11:24            807 GetXYZFromArray.vb
#####             2019/6/23    11:25            340 GetXYZFromPoint.vb
#####             2019/6/23    11:25            157 GetYIntercept.vb
#####             2019/6/23    11:25            261 HasAngleBetween.vb
#####             2019/6/23    11:26            254 HasArea.vb
#####             2019/6/23    11:26            229 HasCOG.vb
#####             2019/6/23    11:27            185 HasHOffset.vb
#####             2019/6/23    11:27            379 HasPackage.vb
#####             2019/6/23    11:28            187 HasParent.vb
#####             2019/6/23    11:29            269 HasRadius.vb
#####             2019/6/23    11:29            312 HasVolume.vb
#####             2019/6/23    11:29            214 HybridShapeExists.vb
#####             2019/6/23    11:30            248 HybridShapeExistsInHybridBody.vb
#####             2019/6/23    11:30            588 ImmediateAnnotation.vb
#####             2019/6/23    11:30            167 Is64Bit.vb
#####             2019/6/23    11:31            194 IsAppOpen.vb
#####             2019/6/23    11:31            288 IsConvertibleToNumber.vb
#####             2019/6/23    11:31            531 IsCurveAbove.vb
#####             2019/6/23    11:32            601 IsIntersectionResultCurve.vb
#####             2019/6/23    11:33            594 IsMidPtCoordToFarFromCurve.vb
#####             2019/6/23    11:33            182 IsNumber.vb
#####             2019/6/23    11:33            554 IsObjInSetWithinDist.vb
#####             2019/6/23    11:34            205 IsPartDocument.vb
#####             2019/6/23    11:34            207 IsPlanar.vb
#####             2019/6/23    11:34            715 IsProductActive.vb
#####             2019/6/23    11:35            217 IsProductDocument.vb
#####             2019/6/23    11:35            240 IsSmartUpdatable.vb
#####             2019/6/23    11:35            173 IsSpace.vb
#####             2019/6/23    11:36            516 IsSurfaceAbove.vb
#####             2019/6/23    11:36            183 IsUpdatable.vb
#####             2019/6/23    11:36            215 IsUpdatableInPart.vb
#####             2019/6/23    11:38            449 KeepBiggestSplit.vb
#####             2019/6/23    11:47            626 KeepCurveSplitByLength.vb
#####             2019/6/23    11:48            757 KeepHighestLevel.vb
#####             2019/6/23    11:48            669 KeepSmallerCurvePar.vb
#####             2019/6/23    11:50            449 KeepSmallestSplit.vb
#####             2019/6/23    11:50            502 KeepSolidSplitByIntersection.vb
#####             2019/6/23    11:51            907 KeepSolidSplitByVolume.vb
#####             2019/6/23    11:51           1370 KeepSolidSplitByVolumeInPart.vb
#####             2019/6/23    11:52            620 KeepSplitByArea.vb
#####             2019/6/23    11:52           1017 KeepTrimOrientation.vb
#####             2019/6/23    11:53            794 LineFromArcEndPts.vb
#####             2019/6/23    11:53            490 LoadExtRef.vb
#####             2019/6/23    11:54            611 MakeArrayFromExcelColumn.vb
#####             2019/6/23    11:54            369 MakeArrayFromSearch.vb
#####             2019/6/23    11:54            324 MakeArrayMidDoubles.vb
#####             2019/6/23    11:55            611 MakeTangentLineAtPt.vb
#####             2019/6/23    11:55            935 MatchBlendOrientationsWithEndPts.vb
#####             2017/6/18    17:18           1782 ModifyFeatureParameters.vb
#####             2019/6/23    11:56           1242 MoveArcSlabCloserToObjByInverse.vb
#####             2019/6/23    11:57            940 MoveArcWallCloserToCoordByInverse.vb
#####             2019/6/23    11:57           1082 MoveAxisSystemXDirFartherFromCoord.vb
#####             2019/6/23    11:57            686 MoveCircle2PointsRadCloserToObj.vb
#####             2019/6/23    12:00            819 MoveCurveParCloserToCoord.vb
#####             2019/6/23    12:01            695 MoveCurveParCloserToObj.vb
#####             2019/6/23    12:02            629 MoveExtremumCloserToObj.vb
#####             2019/6/23    12:03            850 MoveExtrudeCloserToCoord.vb
#####             2019/6/23    12:03            928 MoveLineAngleCloserToCoord.vb
#####             2019/6/23    12:04            673 MoveLineAngleCloserToObj.vb
#####             2019/6/23    12:05            697 MoveLineAngleCloserToObjByNegAngle.vb
#####             2019/6/23    12:06            671 MoveLinePtDirCloserToObj.vb
#####             2019/6/23    12:09            941 MoveLineTangencyCloserToCoord.vb
#####             2019/6/23    12:09            856 MoveOffsetCloserToCoord.vb
#####             2019/6/23    12:09            726 MoveOffsetCloserToObj.vb
#####             2019/6/23    12:10            677 MovePlaneOffsetCloserToObj.vb
#####             2019/6/23    12:10            679 MovePointOnCurveCloserToObj.vb
#####             2019/6/23    12:11            736 MultiRotate.vb
#####             2019/6/23    12:11            285 ParameterFromSubName.vb
#####             2019/6/23    12:11            526 PlacePointOnCurve.vb
#####             2019/6/23    12:12            251 RemoveChars.vb
#####             2019/6/23    12:12            826 ReturnAllObjectsWithinDist.vb
#####             2019/6/23    12:12            502 ReturnMidCurveDist.vb
#####             2019/6/23    12:13            262 ReturnMidPtCoord.vb
#####             2019/6/23    12:13           1356 SelectElement3 Values.vb
#####             2019/6/23    12:13           1262 SelSurfDup.vb
#####              2016/5/6    15:12             19 testvisuperfodraw.txt
#####              2016/5/6    15:12             19 testvisuperfodraw.vb
#####             2021/7/28    23:18           3482 UDF.vb
#####             2015/11/5    22:51          19780 Useful Catia VBA Functions.vb
#####              2017/3/8    16:05          29315 V6_PRODUCT_VBA.mmap

#####              2021/4/6    17:15                AssemblyConstraints
#####          2020/11/21    22:40                AssemblyScript
#####           2021/7/30    18:13                CATIA_EXCEL
#####          2020/11/20     0:18                command
#####              2021/4/6    17:15                DPM_MHI
#####              2021/4/6    17:15                FrameTitleBlock
#####              2021/4/6    17:15                FTA
#####              2021/4/6    17:15                ImmersiveLogon
#####          2020/11/17     6:43                PointInstantiatorFromExcelR5
#####              2021/4/6    17:15                PowerCopy
#####              2021/4/6    17:15                SmarTeam
#####              2021/4/6    17:15                UserFeature
#####          2020/11/17     6:43                vba
#####             2021/7/30    18:14            800 BatchRunKP.CATScript
#####             2012/7/16    13:33          13640 CAAGsiCreateStair.CATScript
#####             2013/4/19    18:47            724 CATIA_Version.CATScript
#####             2013/9/27    22:57          23018 CATSelectObjectCase.CATScript
#####            2020/10/29    13:09            423 Create_New_Body.CATScript
#####             2021/7/30    18:13           2240 CreateAxisFromExcel.CATScript
#####             2013/3/29    18:42           6457 CreateGridlineinCATIAdrawing.catscript
#####             2014/7/10    16:34           3593 CreateNewParameter.CATScript
#####            2005/10/25    18:41           3415 CreatePointsCurvesSweptSurface.CATScript
#####              2020/7/3     0:20           6296 DeleteBeamUDFFromProduct.CATScript
#####              2020/7/3     0:33           5021 DeleteCurrentPartBeamUDF.CATScript
#####             2014/7/10    16:34           3678 DeleteExistParameter.CATScript
#####              2020/7/3     1:12           1660 DeleteObject.CATScript
#####              2013/6/5    21:10          35469 DrawingTitle.CATScript
#####            2013/12/22     9:57           8631 e3develop.catvbs
#####             2021/7/30    17:53            932 ExtractBodyBoundary.CATScript
#####             2021/7/30    17:06           9061 FORMWORKEXTRACTION.CATScript
#####            2014/12/11    13:08          14395 GAS-7.CATScript
#####             2014/4/13    21:54           4351 General-Parameters_and_Measure-Knowledge_Environment.catvbs
#####             2013/3/25    19:33           1733 GenerateUVPts.CATScript
#####             2020/7/23    14:09            965 GetDistance.CATScript
#####              2020/7/2    17:58             54 GetTypeName.CATScript
#####              2020/7/2    17:55             44 HelloWorld.CATScript
#####             2020/8/21     1:14            997 Instantiate_UDF.CATScript
#####            2020/11/14    23:02            954 InstantiateUDFAndPowerCopy.CATScript
#####              2014/3/8    15:26           2562 InstantiationofaPowerCopy.catvbs
#####             2019/6/18    10:53           1134 Macro2.catvbs
#####             2014/8/16    13:51           5191 PrintTree.catvbs
#####             2014/12/3    12:44          30584 PslTubingExtract.CATScript
#####             2017/6/28    13:11           5540 RailwayDesign-V1.catscript
#####             2017/6/25    16:01           3660 REACTION.catscript
#####             2015/1/25    14:01           3744 Rename_Instance.CATScript
#####             2019/7/20     9:55            251 Rename_Object.catvbs
#####             2020/12/4    23:11             21 rename.bat
#####              2007/4/4     8:45           7351 ReviewProductOrPartFTA.catvbs
#####             2005/6/22    17:53           5567 SelectBrokenConstaints.catvbs
#####             2013/5/10    20:15          13638 Stairs.catvbs
#####            2020/10/29    13:17             93 TypeName.CATScript
#####              2017/2/1     6:00            270 UpgradeActiveDocumentMacro.CATScript
#####             2017/6/27    16:56           1232 VB_INSTANTIATE_UDF.CATScript
#####             2013/3/30     0:37            652 VBScript-InputSurface-OutputVerticesasPoints.CATScript

#####             2021/7/26    23:20                ACAD
#####          2020/11/21    22:21                AssemblyConstraints
#####          2020/11/21    22:21                Block
#####          2020/11/21    22:21                Bridge_For_YMA_Code_20190429
#####          2020/11/21    22:21                CATIA-vba-最小包围
#####          2020/11/21    22:21                ColorFilter
#####          2020/11/21    22:21                ConstructionAdministration
#####          2020/11/21    22:21                CostEstimation
#####          2020/11/21    22:21                DoorOrWindowDataSheets
#####          2020/11/21    22:21                DoorsAndWindows
#####          2020/11/21    22:21                DP_API
#####          2020/11/21    22:21                DrawingGeneration
#####          2020/11/21    22:21                DWGImport
#####          2020/11/21    22:21                excel2surface
#####          2020/11/21    22:21                ExportSlab
#####          2020/11/21    22:21                File_Dir_ManagementV2
#####          2020/11/21    22:21                FrameTitleBlock
#####          2020/11/21    22:21                FTA
#####          2020/11/21    22:21                GridFactory
#####          2020/11/21    22:21                MultiEdit
#####          2020/11/21    22:21                PartList
#####          2020/11/21    22:21                PartNumber
#####          2020/11/21    22:21                PowerCopy
#####          2020/11/21    22:21                qhull
#####          2020/11/21    22:21                SectionDrawing
#####          2020/11/21    22:21                ShellExpensionButts
#####          2020/11/21    22:21                SmarTeam
#####          2020/11/21    22:21                Solar_Render_Tool
#####          2020/11/21    22:21                Solar_Render_Tool_V0R2
#####           2021/2/11     0:33                sucdri_bridge
#####          2020/11/21    22:21                SurfaceExtractions
#####          2020/11/21    22:21                UserFeature
#####          2020/11/21    22:21                Using_Attributes
#####          2020/11/21    22:21                Using_ColorFilter
#####          2020/11/21    22:21                Using_Proxy
#####            2020/11/21    22:21         163840 3dtags.catvba
#####            2020/11/21    22:21         147456 AngleReference_R4.catvba
#####            2020/11/21    22:21         131072 Animation.catvba
#####            2020/11/21    22:21         720896 AnimForm.catvba
#####            2020/11/21    22:21         180224 Annotations.catvba
#####            2020/11/21    22:21         147456 AnSSearch_V0R2.catvba
#####            2020/11/21    22:21         163840 AppendLengthsFromAxis_V0R1.catvba
#####            2020/11/21    22:21         147456 ArcBeamFactoryVB.catvba
#####            2020/11/21    22:21         131072 ArcContourOpnFactoryVB.catvba
#####            2020/11/21    22:21         212992 ArcMemberExportVB1.catvba
#####            2020/11/21    22:21         131072 ArcSpaceFactoryVB.catvba
#####            2020/11/21    22:21         180224 ArcViews.catvba
#####            2020/11/21    22:21         423424 asset.catvba
#####              2015/9/5    20:02        1458176 AutoDP.catvba
#####            2020/11/21    22:21         311296 AutomatedPowerCopy_V0R1.catvba
#####            2020/11/21    22:21         393216 AutomatedPowerCopy_V0R2.catvba
#####            2020/11/21    22:21         357376 AutomatedPowerCopy_V0R2b.catvba
#####            2020/11/21    22:21         393216 AutomatedPowerCopy_V0R3.1.catvba
#####              2008/5/5    16:32         393216 AutomatedPowerCopy_V0R3.catvba
#####            2020/11/21    22:21         196608 BatchCATPartFromCATProduct_V0R1.catvba
#####            2020/11/21    22:21         196608 BatchCATPartFromCATProduct_V0R2.catvba
#####            2020/11/21    22:21         491520 BatchExtrusion.catvba
#####            2020/11/21    22:21         196608 BatchPartNumberRename_V0R2.catvba
#####            2020/11/21    22:21         147456 BatchUnfold.catvba
#####            2020/11/21    22:21          84992 BodyViews.catvba
#####            2020/11/21    22:21         146432 Browser.catvba
#####            2020/11/21    22:21         229376 CATIASORT_New.catvba
#####            2020/11/21    22:21         180224 CATIASORT.catvba
#####            2020/11/21    22:21         180224 ChangeParameter.catvba
#####             2019/6/23    11:08         138752 CircleOnPoints.catvba
#####            2020/11/21    22:21          79872 Closed_Profile.catvba
#####            2020/11/21    22:21         212992 ColorFilter.catvba
#####            2020/11/21    22:21         212992 ColOutput.catvba
#####            2020/11/21    22:21         147456 ColumnsAndBeams.catvba
#####            2020/11/21    22:21         198144 ComponentRemovalByIntersection_V0R1.catvba
#####            2020/11/21    22:21         573440 ConstructionAdministration.catvba
#####            2020/11/21    22:21          98304 ConvertDatumPtsToLive.catvba
#####            2020/11/21    22:21          98304 Copy and Paste from Part to Part.catvba
#####            2005/10/31    13:21           4168 CreateFillInSurfaceArray.bas
#####            2005/10/25    18:41           3415 CreatePointsCurvesSweptSurface.bas
#####             2005/11/1    15:49           3233 CreateUserDefinedPlanesOnCurve.bas
#####             2011/8/24    21:28         163840 CurvatureAnalysis.catvba
#####            2020/11/21    22:21         215040 CurveOptimizerSetup_V0R1.catvba
#####            2020/11/21    22:21         229376 CurveOptimizerSetup_V0R3.catvba
#####            2011/12/30    18:04       28358551 Custom UDF-pattern - part 1 - YouTube.flv
#####            2020/11/21    22:21         327680 Datumizer.catvba
#####            2020/11/21    22:21         131072 DeleteObjByLength.catvba
#####            2020/11/21    22:21         169472 DELMIA_XUS_MAIN.catvba
#####            2020/11/21    22:21         131072 DevSurfFactory.catvba
#####            2020/11/21    22:21         180224 Diagonalizer_Web_V0R1.catvba
#####            2020/11/21    22:21         229376 DoorOrWindowDataSheet.catvba
#####            2020/11/21    22:21         262144 DoorOrWindowDataSheetR2toR3.catvba
#####            2020/11/21    22:21         147456 Drawing_All.catvba
#####            2020/11/21    22:21          81920 DwgImp.catvba
#####            2020/11/21    22:21         119296 EditNames.catvba
#####              2008/4/1    12:07         360448 ExcelProductStructure_V0R2.catvba
#####            2020/11/21    22:21         114688 ExIFCobjects.catvba
#####            2020/11/21    22:21         114688 ExpDWGobjs.catvba
#####            2020/11/21    22:21         196608 Export Spot Information for Ruixiang.catvba
#####            2020/11/21    22:21         212992 ExportSlab.catvba
#####            2020/11/21    22:21         491520 ExportViews_V0R2.catvba
#####            2020/11/21    22:21         491520 ExportViews.catvba
#####            2020/11/21    22:21         491520 ExtractDrawings.catvba
#####            2020/11/21    22:21         344064 Extractor_Units.catvba
#####            2020/11/21    22:21         111104 ExtRefSetting.catvba
#####             2021/5/13    23:37         196608 FacadeDesign.catvba
#####            2020/11/21    22:21         196608 FEMFactory.catvba
#####            2020/11/21    22:21          98304 File Save.catvba
#####            2020/11/21    22:21       13484032 file_cleanup.catvba
#####              2021/5/8    22:55         163840 File_Dir_Management.catvba
#####             2021/4/26    23:31         180736 File_Dir_ManagementV2.catvba
#####            2020/11/21    22:21         180224 FileBrowser (2).catvba
#####            2020/11/21    22:21         180224 FileBrowser.catvba
#####            2020/11/21    22:21         395264 FinishesGenerator (2).catvba
#####            2020/11/21    22:21         395264 FinishesGenerator.catvba
#####            2020/11/21    22:21         395264 FormworkGenerator (2).catvba
#####            2020/11/21    22:21         395264 FormworkGenerator.catvba
#####            2020/11/21    22:21         131072 GeneratePublications_V0R1.catvba
#####            2020/11/21    22:21         131072 GeneratePublications_V0R2.catvba
#####            2020/11/21    22:21          84480 GenerateUVPts.catvba
#####            2020/11/21    22:21         274944 GenerativeParameters.catvba
#####             2009/4/28    10:33            166 GeodesicCrv.CATGScript
#####            2020/11/21    22:21         131072 GetTimeStamp.catvba
#####            2020/11/21    22:21          81920 GSD_CAAGsiCreateStair.xls
#####            2020/11/21    22:21          65024 GSD_PointSplineLoftFromExcel_BeforeV5R12.xls
#####            2020/11/21    22:21          76288 GSD_PointSplineLoftFromExcel.xls
#####            2020/11/21    22:21         131072 GTCAttReporter.catvba
#####            2020/11/21    22:21          65536 ImportIfc.catvba
#####            2020/11/21    22:21          81920 InstanceRenamer_V0R1.catvba
#####             2009/1/10    15:40            170 IsoU.CATGScript
#####             2009/1/10    15:41            170 IsoV.CATGScript
#####            2020/11/21    22:21         245760 KP_STANDARD_SCRIPTS.catvba
#####             2011/9/10    20:59         344064 LabelDrawing_V7.catvba
#####            2020/11/21    22:21         171008 LineBesector_V0R1.catvba
#####            2020/11/21    22:21         171008 LineBesector_V0R2.catvba
#####            2020/11/21    22:21         131072 LinkDitto.catvba
#####            2020/11/21    22:21         180224 LoadReplaceLinks.catvba
#####            2020/11/21    22:21         294912 LVMH.catvba
#####             2019/5/16    16:31           6318 MacroGenViewSurBody_SupportPlaneinUnfoldbody.txt
#####            2020/11/21    22:21         163840 MemberOffsets.catvba
#####            2020/11/21    22:21         557056 MergeDMU.catvba
#####            2020/11/21    22:21         172544 Mesh.catvba
#####            2020/11/21    22:21         114688 ModelUpgrade.catvba
#####            2005/10/31    19:17           3961 Mohamed_Macrofile.bas
#####             2009/11/3    11:04         350208 MultiSplit_V0R10.catvba
#####            2020/11/21    22:21         344064 MultiSplit_V0R8.catvba
#####            2020/11/21    22:21         491520 MultiSplit.catvba
#####            2020/11/21    22:21         131072 MultiSupportBeam.catvba
#####            2020/11/21    22:21         491520 MyVBA.catvba
#####            2020/11/21    22:21         180224 PanelAssembly.catvba
#####            2020/11/21    22:21         163840 PanelPostChecker_V0.catvba
#####            2020/11/21    22:21         180224 PanelPostChecker_V0R2.catvba
#####            2020/11/21    22:21         376832 Partinator_V0R1.catvba
#####             2009/1/29    18:21         376832 Partinator_V0R2.catvba
#####            2020/11/21    22:21         491520 PlanesFromSections.catvba
#####            2020/11/21    22:21         146432 PointInstantiatorFromExcelR2 (2).catvba
#####            2020/11/21    22:21         163840 PointInstantiatorFromExcelR2.catvba
#####            2020/11/21    22:21         131072 PointInstantiatorFromExcelR5.catvba
#####            2020/11/21    22:21         245760 PowerCGR_V2-0.catvba
#####            2020/11/21    22:21         114688 Product_Dumb_Down (2).catvba
#####            2020/11/21    22:21         114688 Product_Dumb_Down.catvba
#####             2014/1/11    22:19         491520 QHull_Mesh_Generation.catvba
#####            2020/11/21    22:21         153950 QHull_Mesh_Generation.zip
#####            2020/11/21    22:21          91409 qhull-1.0.tar.gz
#####            2020/11/21    22:21        3229784 qhull-2019.1.zip
#####             2019/7/17    18:14         311296 RAILWAY_BEAM_CREATE_INTERNAL_BOX.catvba
#####            2020/11/21    22:21          81920 ReactionsForChangingColor.catvba
#####            2020/11/21    22:21         114688 RenameGeometryInPart_V0.catvba
#####            2020/11/21    22:21          86528 RenameTree (2).catvba
#####            2020/11/21    22:21          86528 RenameTree.catvba
#####            2020/11/21    22:21         147456 RFL_STANDARD_SCRIPTS.catvba
#####            2020/11/21    22:21         212992 SlabFactory.catvba
#####            2020/11/21    22:21         196608 Slider.catvba
#####            2020/11/21    22:21         481792 Solar_Render_Tool_V0R2.catvba
#####            2020/11/21    22:21         163840 sun.catvba
#####            2020/11/21    22:21         175616 surface.catvba
#####            2020/11/21    22:21         131072 TessFactory.catvba
#####            2020/11/21    22:21         212992 Test - 副本.catvba
#####              2008/1/5    12:57         212992 TitleBlockGeneration_V0R1.catvba
#####            2020/11/21    22:21         166912 TopoSurfaceMaker_V0R1.catvba
#####            2020/11/21    22:21         131072 TraverseDoorWindows.catvba
#####            2011/12/24    16:28       11965253 Tutorial 06 Replacing a control point with a spline - YouTube.flv
#####            2011/12/24    16:37       22203921 Tutorial 07 Creating a grid of boxes with UDFs - YouTube.flv
#####            2011/12/24    16:27       17169416 Tutorial02_Modeling_A_Table.mp4 - YouTube.flv
#####            2020/11/21    22:21         475136 UniformatCostEstimation (2).catvba
#####            2020/11/21    22:21         475136 UniformatCostEstimation.catvba
#####            2020/11/21    22:21         278528 VBA_01.catvba
#####            2020/11/21    22:21         737280 VBA_MAIN.catvba
#####            2020/11/21    22:21          98304 VBA_RENAME.catvba
#####            2020/11/21    22:21         131072 VBA.catvba
#####            2020/11/21    22:21         196608 VBAForBridgeDesign.catvba
#####            2020/11/21    22:21         147456 VBAHIDESHOW.catvba
#####              2021/2/8    13:26         114688 VBAProject1 (2).catvba
#####            2020/11/21    22:21         196608 VBAProject1 (3).catvba
#####             2021/12/3    15:34         513024 VBAProject1.catvba
#####            2020/11/21    22:21         180224 VBARename.catvba
#####            2020/11/21    22:21         196608 VBAXMLexample (2).catvba
#####            2020/11/21    22:21         196608 VBAXMLexample.catvba
#####            2020/11/21    22:21         147456 Walls.catvba
#####            2020/11/21    22:21         376832 WANDA_01.catvba
#####            2020/11/21    22:21         135680 WriteTree (2).catvba
#####            2020/11/21    22:21         135680 WriteTree.catvba
#####             2016/6/30    16:06         147456 xus (2).catvba
#####            2020/11/21    22:21         819200 XUS_AUTOMATIONS.catvba
#####            2020/11/21    22:21         327680 XUS-AUTOMATION-VBA.catvba
#####             2021/7/30    17:11         180224 xus.catvba
#####            2020/11/21    22:21         180736 XYZTextAnnotations_V0R1.catvba
#####            2020/11/21    22:21         327680 XYZTextAnnotations_V0R2.catvba

Mode                 LastWriteTime         Length Name

----                 -------------         ------ ----

#####             2021/11/4     1:34           7797 CAAGetGeometricFromFeature.cpp
#####             2021/11/4     1:34           3594 CAAGetPartCore.cpp
#####             2021/11/4     1:34           2605 CAAHighlight.cpp
#####             2021/11/4     1:34           1103 CAAMessage.cpp
#####             2021/11/4     1:34           9948 CAAObjectOperating.cpp


#####              2021/6/5     1:29           1514 AddStartUsedHistory.cpp
#####              2021/6/5     1:29           1758 CAACopyGeoObjectFromOneContainerToAnotherContainer.cpp
#####              2021/6/5     1:30            399 CAADelete.cpp
#####              2021/6/5     1:30            592 CAAGetBody.cpp
#####              2021/6/5     1:30           1330 CAAGetCurveTypeFromMeasurableInContext.cpp
#####              2021/6/5     1:30            770 CAAGetDistance.cpp
#####              2021/6/5     1:30           3803 CAAGetGeometricFromFeature.cpp
#####              2021/6/5     1:30            507 CAAGetGeometricType.cpp
#####              2021/6/5     1:30            615 CAAGetLength.cpp
#####              2021/6/5     1:30           2244 CAAGetPrtContainer.cpp
#####             2021/11/6    22:32           2313 CAAGsiSearchFeatureFromName.cpp
#####              2021/6/4    19:16            725 CAAHideElements.cpp
#####              2021/6/5     2:13           2172 CAAHighlight.cpp
#####            2021/11/10     0:19          50757 CAAktService.cpp
#####              2021/6/5     1:30           2893 CAAMcaGetGeometry.cpp
#####              2021/6/5     1:31            597 CAAMessage.cpp
#####              2021/6/5     1:31            485 CAASetInsert.cpp
#####              2021/6/5     1:31           2536 CAASetObjectColor.cpp
#####              2021/6/5     1:31           2089 CAASetObjectHideOrShow.cpp
#####              2021/6/5     1:42            275 CAAUpdate.cpp
#####              2021/6/5     1:31            979 ChanceInstanceName.cpp
#####              2021/6/5     1:31            797 Close.cpp
#####              2021/6/5     1:31            502 CreateAngle.cpp
#####              2021/6/5     1:31           1964 CreateChildrenPrds.cpp
#####              2021/6/5     1:31            489 CreateDirection.cpp
#####              2021/6/5     1:31           1028 CreateDirectory.cpp
#####              2021/6/5     1:59            810 CreateDirectory1.cpp
#####              2021/6/5     1:31            502 CreateLength.cpp
#####              2021/6/5     1:31            489 CreateReal.cpp
#####              2021/6/5     1:31            421 DirExists.cpp
#####              2021/6/5     1:31            574 DisableString.cpp
#####              2021/6/5     1:31           1016 Featurize.cpp
#####              2021/6/5     1:32           4026 GetAxisBRep.cpp
#####              2021/6/5     1:46            559 GetDocumentFromPrd.cpp
#####              2021/6/5     1:32            664 GetElementListFromGeomSet.cpp
#####             2021/11/6    22:27            412 GetEnvValue.cpp
#####              2021/6/5     1:32            994 GetExcelFilesFromFolder.cpp
#####              2021/6/5     1:32            443 GetObjAlias.cpp
#####              2021/6/5     1:32           1279 GetPathFromPartNumber.cpp
#####              2021/6/5     1:32           1264 GetPrtContainer.cpp
#####              2021/6/5     1:32           2400 GetResourcePath.cpp
#####              2021/6/5     1:32           1090 GetRootProduct.cpp
#####              2021/6/5     1:32            628 GetRootProductFromDocument.cpp
#####              2021/6/5    12:52            126 HelloWorld.cpp
#####              2021/6/5     1:32           1347 InitSession.cpp
#####              2021/6/5     1:32           1226 IsProduct.cpp
#####              2021/6/5     1:32           1954 LengthJudgeColor.cpp
#####              2021/6/5     1:33            692 MessageOutputError.cpp
#####              2021/6/5     1:33            692 MessageOutputInfo.cpp
#####              2021/6/5     1:33            700 MessageOutputWarning.cpp
#####              2021/6/5     1:33           1143 ModifyColor.cpp
#####              2021/6/5     1:33           1884 New.cpp
#####              2021/6/5     1:33           1564 Open.cpp
#####              2021/6/5     1:33            899 Save.cpp
#####              2021/6/5     1:33           1032 SaveModuleTree.cpp
#####              2021/6/5     1:33           1433 SaveProduct.cpp
#####              2021/6/5     1:33           1037 SaveSingleProduct.cpp
#####              2021/6/5     1:33            413 SetObjAlias.cpp
#####              2021/6/5     1:33            550 StringBuildFromChar.cpp
#####              2021/6/5     1:33            405 StringConvertToChar.cpp
#####              2021/6/5     1:33            449 StringConvertToWChar.cpp
#####              2021/6/5     1:33            529 ThrowLastErrorMessage.cpp
#####              2021/6/5     1:33            520 WriteErrorLog.cpp



#####              2021/6/5    15:58           4507 CAAUDFOneAxis.cpp