# 3DEXPERIENCE_Forms

新增了基于达索 3DEXPERIENCE CATIA R2020x 的UI样式库

# Interface

``` cs

```

```


using HybridShapeTypeLib;
using MECMOD;
using System;
using System.Collections;
using INFITF;


using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using KnowledgewareTypeLib;

namespace CATObjectModelerLibrary
{
    public interface AECISteelBridge
    {
        //创建加强肋
        ArrayList CreateRibBySurface(MECMOD.Part part, HybridShape isurface);

    }

    public interface CATAECIASPBBCushion
    {
        AnyObject InstantiateCushion(MECMOD.Part part, AnyObject UDF, string[] UDFValue, string[] UDFParametersName, string[] UDFParametersValue,string InputAxisName);
        void InstantiateCushionInOneSet(Part part, AnyObject UDFSets, string AxisName,string GeoSetName);

        void InstallCushion(ArrayList BeamGeoList);
       
    }
    public interface CATAECAlignment
    {
        HybridShape CreatNewRoadBoundary(HybridShape OriCurve, HybridShape CenterCurve, ArrayList CenterAlignmentAxisSystemesList,ArrayList CheckResultBoolean);
    }

    //public interface AECAxisSystems
    //{
    //    void CreatAxisFromExcel();
    //    void ExportAxisAngleAndHeight();

    //}

    //public interface InstantiateUDF
    //{
    //    string UdfName { get; set; }
    //}


    //public interface AECCivilRoad
    //{
    //    void CreatRoadBoundary();
    //}


    public interface CATIRailwayBridgeModeler
    {
        void CreateInternalBeamSpace(Part part, HybridShape Curve, HybridShape bottomCrv, HybridShape StartPoint, OrderedGeometricalSet hb, out ArrayList iPlanelist);
        HybridShape CreatePolyLineBaseOnPlane(HybridShapeFactory hsf, HybridShape iPlane, HybridShape iPt, OrderedGeometricalSet hb);
        HybridShape CreateLoftFromMultiSection(Part part, ArrayList iSectionlist, OrderedGeometricalSet hb);
        HybridShape CreateLoftFromMultiSectionBaseOnUDF(Part part, ArrayList iUDFset, OrderedGeometricalSet hb, HybridShape ispline, int CouplingCount);
        void CreateInternalSection(Part part, HybridShape iTopCurve, HybridShape iBottomCurve, HybridShape iPlane, OrderedGeometricalSet DestinationHybridBody);
        AnyObject InstantiateUDFInternalSection(MECMOD.Part part, string pwname, string iname, string iversion, HybridShape iTopCurve, HybridShape iBottomCurve, HybridShape iPlane);
        void CreatePanelFromList(Part part, ArrayList DistanceList, HybridShape iPlane, OrderedGeometricalSet destinationHB, bool dir, HybridShape topcurve, HybridShape bottomcurve);

    }

    public interface CATRailWayStandardBeamBridge
    {

        void CreateStandardBeam(Part part, HybridShape iStartPoint, HybridShape iSurface, HybridShape iCurve, HybridShape iPlanerCurve, HybridBody iOHB, double iDistance1, double iDistance2, double iDistance3, double iDistance4);

        HybridShape CreateSectionFromPointList(HybridShapeFactory hsf);
    }



    public interface CATIRailwayBridgeModeler1
    {

        void CreateStandardBeam(Part part, HybridShape iStartPoint, HybridShape iSurface, HybridShape iCurve, HybridShape iPlanerCurve, HybridBody iOHB, double iDistance1, double iDistance2, double iDistance3, double iDistance4);

        HybridShape CreateSectionFromPointList(HybridShapeFactory hsf);

    }


    public interface CATRailWayStandardBeamBridge1
    {

        void CreateInternalShapesT1(Part part, ArrayList distanceArray, bool dircheck, HybridShape opt);
        void CreateInternalShapesT2(Part part, ArrayList distanceArray, bool dircheck, HybridShape opt);
        void CreateInternalShapesT3(Part part, ArrayList distanceArray, bool dircheck, HybridShape opt);



        void CreateStandardBeam(Part part, HybridShape iStartPoint, HybridShape iSurface, HybridShape iCurve, HybridShape iPlanerCurve, HybridBody iOHB, double iDistance1, double iDistance2, double iDistance3, double iDistance4);

        HybridShape CreateSectionFromPointList(HybridShapeFactory hsf);
    }
}


```