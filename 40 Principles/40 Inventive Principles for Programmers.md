# 40 Inventive Principles for Programmers

This is an adapted and extended version of 40 TRIZ Inventive Principles originally developed by G Altshuller The titles and formulations of the principles might not coincide with the titles and formulations available in other literature about TRIZ and systematic Innovation due to the original nature of research and development performed by ICG T&C to create this document.

This version has been developed by A. Kugushev and is based on the materials by G. Altshuller, R. Fulbright, D. Mann, K. Rea, V. Sushkov, A. Kuryan.

## 01 SEGMENTATION
![](/resources/01.SEGMENTATION.png)
### Strategies and Recommendations
- Divide your system or object into independent parts or interconnected parts.
- Divide your system or object into parts so that some part of it can be easily taken away when necessary.
- Assemble your system or object from smaller segments.
- Increase the degree of the system’s segmentation by composing the system from a number of smaller various objects or subsystems.
- Break a process or activity to smaller segments.
- Increase the degree of segmentation of homogeneous systems or processes.
- Increase the difference between segments.
### Examples
- Follow Interface Segregation Principle and divide a huge interface to multiple interfaces with a dedicated responsibility
- Component based architecture
- Microservices architecture

## 02 TAKING AWAY
![](/resources/02.TAKING%20AWAY.png)
### Strategies and Recommendations
- If some part of your system or your process interferes with other parts or creates a negative effect, “take away” the interfering part of your system or your process by separating it from the system or the process by removing or isolating it from the system or the process. 
- If some property of a system interferes with other properties of functions of the system, find out what part of the system is a carrier of the property and separate it from the system by creating another system or transferring the property to some other part of the system.
- “Single out” the only necessary property of a system by creating another system which has the required property only.  
### Examples
- Creating a standalone service with responsibility that is related to the negative effect
- Process Spawning 
- Creating a dedicated IoC container for a task to locate negative side effects
- Temporary table in SQL



#3
LOCAL QUALITY Examples
Business Systems

In a fast food chain, the inclusion of traditional local meals
can expand the standard menu, making it more diverse

Logistic efficiency can be improved by storing the goods
with similar functions together at a warehouse

Changing the working hours helps arrange interaction of the
people who work within the same project but in different
time zones

Instead of a salesperson, a group of experts of various
profiles can give replies to customers’ questions
Strategies
and Recommendations
o
Instead of a uniform structure of your system or an object,
use a non uniform structure of the system or the object.
o
Instead of a uniform structure of your process, use a non
uniform structure.
o
Vary in time or space the part of your process that causes
problems.
o
Instead of a uniform structure of environment, use a non
uniform structure of environment.
o
If two (or more) different functions have to be performed
by the same part of the system, but this causes problems,
divide this part into two (or more) parts.
o
Make parts of the system and its environment function in
most suitable and proper conditions for each part.
o
Make activities within a process and its environment
function in most suitable and proper conditions for each
activity.
Examples
IT

Software localization language and time zone settings
date and number formats, and other

Highlighting the current data field and format in data entry
forms

Special marking of mandatory fields in data entry forms

Having the words with syntax errors u nderlined in text
processors

Applying specific marking of hyperlinks on web pages
6
6
CONFIDENTIAL
CONFIDENTIAL
#4
#4::ASSYMETRYASSYMETRY
Examples
Examples((Business SystemsBusiness Systems))

ProvidingProvidingseparateseparatebudgetsbudgetstotosubunitssubunitsratherratherthanthanincreasingincreasingorordecreasingdecreasingtheirtheirbudgetsbudgetssimilarlysimilarly

UsingUsingaasymmetricalsymmetricalboxesboxesininthetheproductproductpromotionpromotionthatthatcouldcouldattractattractmoremoreattentionattention

AsymmetricalAsymmetricalevaluationevaluation::onlyonlythetherepliesrepliestotorelevantrelevantquestionsquestionsareareevaluatedevaluated

UsingUsingasymmetricalasymmetricaldesigndesignofofaawebweb--pagepagetotodrawdrawattentionattentiontotothethesitesite
Strategies
Strategiesand Recommendationsand Recommendations
o
oIf your system has an asymmetrical structure or shape, If your system has an asymmetrical structure or shape, consider making it asymmetrical.consider making it asymmetrical.
o
oIf your system is asymmetrical, increase the degree of If your system is asymmetrical, increase the degree of asymmetry.asymmetry.
o
oChange the degree of asymmetry by varying the asymmetry Change the degree of asymmetry by varying the asymmetry dynamically depending on the operating conditions.dynamically depending on the operating conditions.
o
oIncrease or decrease the degree of symmetry in processes Increase or decrease the degree of symmetry in processes depending on the operating conditions and required depending on the operating conditions and required effects.effects.
Examples
Examples((ITIT))

TheTheasymmetricalasymmetricalcodingcodingalgorithmalgorithmisismoremorestablestablebecausebecauseititusesusesthethedifferentdifferentkeyskeysforforencodingencodingandanddecodingdecoding..

TheTheasymmetricalasymmetricalcompressioncompressionalgorithmalgorithmrequiresrequiresmoremoreCPUCPUresourcesresourcesforforimageimagecompressioncompressionthanthanforforimageimagedecompressiondecompression..

WindowsWindowsautomaticallyautomaticallygeneratesgeneratesthethevirtualvirtualmemorymemorydependingdependingononthetheRAMRAMsizesizeandandfreefreeHDDHDDspacespace
7
7
CONFIDENTIAL
CONFIDENTIAL
#
#5:5:MERGINGMERGING
Examples
Examples((Business SystemsBusiness Systems))

ForForananunknownunknownmarketmarketpenetration,penetration,creatingcreatingaajointjointventureventureofoftwotwosimilarsimilarcompanies,companies,whichwhichoperateoperateinindifferentdifferentcountriescountries..

InInTokyoTokyothethefiberfiber--opticopticcablecablelineslinesareareplacedplacedwithinwithinthetheexistingexistingwaterwatersupplysupplysystems,systems,permittingpermittingtotosavesavespacespaceandandmakingmakingthetherequiredrequiredearthworkearthworkoperationsoperationsunnecessaryunnecessary..

IfIfthetherequiredrequiredcompetencescompetencesareareinindeficit,deficit,ititisispossiblepossibletotohirehiretotoaasinglesinglepositionpositiontwotwocandidatescandidateswhowhohavehavestrongerstrongerskillsskillsininoneoneareaareaandandweaker,weaker,ininanotheranother..
Strategies
Strategiesand Recommendationsand Recommendations
o
oMerge identical (or similar) parts orMerge identical (or similar) parts orcomponents of a components of a system in space.system in space.
o
oMerge identical (or similar) parts orMerge identical (or similar) parts orcomponents of a components of a system in time.system in time.
o
oMerge two or more different systemsMerge two or more different systemsto achieve the to achieve the synergetic effect.synergetic effect.
o
oMerge two or more systems toMerge two or more systems toincrease efficiency or to increase efficiency or to save space,save space,time, energy, or any other resources.time, energy, or any other resources.
o
oMerge two or more different processesMerge two or more different processesinto a single into a single process.process.
o
oTransfer activities from one processTransfer activities from one processto another process.to another process.
Examples
Examples((ITIT))

DistributedDistributeddatabasesdatabases;;distributeddistributedcalculationscalculations;;distributeddistributedqueriesqueriestotoheterogeneousheterogeneousdatadatasourcessources

MailMailconsolidationconsolidationviavialetterletterthreadsthreadsininaamailmailsystemsystem

MergingMergingthetheCSSCSSstylesstylesononwebweb--pagespages

DatabaseDatabaseaggregativeaggregativeindexindexisisaamergermergerofofseveralseveralsimplesimpleindexesindexes

CreatingCreatinguserusergroupsgroupswithwithsimilarsimilaraccessaccesspermissionspermissions
8
8
CONFIDENTIAL
CONFIDENTIAL
#6
#6::UNIVERSALITYUNIVERSALITY
Examples
Examples((Business SystemsBusiness Systems))

HiringHiringananemployeeemployeewhowhohashasbothbothtechnicaltechnicalandandmanagerialmanagerialcompetenciescompetencies

“One“One--stopstopshopping”shopping”——aagasgasstationstationwherewhereoneonecancanbuybuyfuel,fuel,ananinsurance,insurance,bankbankservices,services,foodstuffs,foodstuffs,andandsosoonon

MergingMergingthethepartspartsofofdifferentdifferentprocessesprocessesthatthatconsumeconsumethethesamesameresourcesresources

“Well“Well--beingbeingstore”store”——ananonlineonlinefoodfoodsupermarketsupermarketwherewhereoneonecancangetgetananadviceadvicefromfromaadietdietconsultantconsultant

eBayeBay——aauniversaluniversalauctionauction
Strategies
Strategiesand Recommendationsand Recommendations
o
oIf you have several objects or systems delivering different If you have several objects or systems delivering different functions, consider creating a new single system that could functions, consider creating a new single system that could deliver these functions thus eliminating the need for having deliver these functions thus eliminating the need for having several different systems.several different systems.
o
oIf you have several separate different processes delivering If you have several separate different processes delivering different functions, consider creating a single process that different functions, consider creating a single process that will deliver a multiple functionality.will deliver a multiple functionality.
Examples
Examples((ITIT))

VirtualVirtualmachinemachine((forforexampleexample,,JavaJavaVirtualVirtualMachineMachine))thatthatprovidesprovidesthetheexecutionexecutionofofcodecodeindependentlyindependentlyfromfromhardwarehardwareandandoperatingoperatingsystemsystem

MultilingualMultilingualcapabilitycapabilityofofsoftwaresoftware

USBUSBandandminimini--USBUSBasasuniversaluniversalinterfacesinterfacestotogetgetvariousvariousdevicesdevicesconnectedconnected

UUIDUUID——aauniqueunique(that(thatis,is,universal)universal)informationinformationobjectobjectidentifieridentifier

URLURL——aauniversaluniversalwebweb--pagepageaddressaddressininthethenetworknetwork
9
9
CONFIDENTIAL
CONFIDENTIAL
#7
#7::NESTINGNESTING
Examples
Examples((Business SystemsBusiness Systems))

Hierarchical organizational structureHierarchical organizational structureof an entity:of an entity:divisions, divisions, departments, directorates, sections, and groupsdepartments, directorates, sections, and groups

Companies inside corporates or holding companiesCompanies inside corporates or holding companies

Profit centers inside entitiesProfit centers inside entities

WarehouseWarehouse--atat--warehousewarehouse

Orienting to the customer’s hierarchy when rolling out a Orienting to the customer’s hierarchy when rolling out a new productnew product

In the hierarchical work breakdown structure In the hierarchical work breakdown structure ((WBSWBS)),,a a complex task is detailed by a set of smaller tasks it consists complex task is detailed by a set of smaller tasks it consists ofof
Strategies
Strategiesand Recommendationsand Recommendations
o
oPlace an object or a system inside another system.Place an object or a system inside another system.
o
oIncrease a number of systems or objects nested.Increase a number of systems or objects nested.
o
oMake one system dynamically become a part of another Make one system dynamically become a part of another system when necessary and then separate the systems system when necessary and then separate the systems again.again.
o
oIntroduce a new process inside an existing process.Introduce a new process inside an existing process.
o
oIncrease a number of “nested” processes.Increase a number of “nested” processes.
o
oMake process activities dynamically appear when needed Make process activities dynamically appear when needed and disappear when not needed.and disappear when not needed.
Examples
Examples((ITIT))

IDEFIDEF00methodologymethodologyallowsallowsrepresentingrepresentingthethesystem’ssystem’sfunctionalfunctionalmodelmodelasasananhierarchyhierarchyofoffunctionsfunctions

UsingUsingthetheframesframesononaawebweb--pagepageallowsallowseditingeditingthethecontentscontentsofofeacheachframeframeindependentlyindependently

DatabaseDatabasenestednestedqueryquerythatthatincludesincludesoneoneororseveralseveralsubsub--queriesqueries

RecursiveRecursivefunctionfunctionthatthatcontainscontainsaacallcall--ininforforitselfitself
10
10
CONFIDENTIAL
CONFIDENTIAL
#8
#8::COUNTERACTIONCOUNTERACTION
Examples
Examples((Business SystemsBusiness Systems))

Inviting twoInviting twoparticipants with opposite views to a discussionparticipants with opposite views to a discussion

Simultaneous development of optimistic and pessimistic Simultaneous development of optimistic and pessimistic scenariosscenariosin risk management practicesin risk management practices

If two companiesIf two companiesare merged, one of them pulls the other are merged, one of them pulls the other by using its strong sides (distribution system, marketing by using its strong sides (distribution system, marketing system, technologies, and other)system, technologies, and other)

Highly profitable goods in supermarkets compensate low Highly profitable goods in supermarkets compensate low profits from other goodsprofits from other goods
Strategies
Strategiesand Recommendationsand Recommendations
o
oIf a certain action by a system causes a negative effect but If a certain action by a system causes a negative effect but the action should be preserved, subject the system to a the action should be preserved, subject the system to a “counterforce”“counterforce”——a reverse action that cancels the negative a reverse action that cancels the negative effect.effect.
o
oConsider dividing a system into parts so that the undesired Consider dividing a system into parts so that the undesired action that produces a negative effect, and the desired action that produces a negative effect, and the desired action compensate each other.action compensate each other.
o
oChange the environment of your system in such a way that Change the environment of your system in such a way that the environment itself introduce such a “counterthe environment itself introduce such a “counter--” or ” or “compensation” force.“compensation” force.
o
oMerge two systems, which deliver opposite functions Merge two systems, which deliver opposite functions (actions), together.(actions), together.
Examples
Examples((ITIT))

Turning on the “power saving” mode in laptop when it is Turning on the “power saving” mode in laptop when it is unplugged from electric networkunplugged from electric network

Use of the special messages likeUse of the special messages like“Please wait”“Please wait”or or “Processing in progress”“Processing in progress”when execution of an operation when execution of an operation takes plenty of timetakes plenty of time

TemporaryTemporarysuspending or closing the operation of apps suspending or closing the operation of apps when a “heavy” app is started that requires considerable when a “heavy” app is started that requires considerable resourcesresources

InclusionInclusionof detailed descriptions, tips, and help of detailed descriptions, tips, and help information into an app along with a new featureinformation into an app along with a new feature
11
11
CONFIDENTIAL
CONFIDENTIAL
#9
#9::PRIOR ANTIPRIOR ANTI--ACTIONACTION
Examples
Examples((Business SystemsBusiness Systems))

AAwellwell--organizedorganized“adverse“adversecriticism”criticism”campaigncampaigncancanswitchswitchthetheaudience’saudience’sattentionattentiontotoaanewnewproductproduct

FailureFailureModeModeandandEffectEffectAnalysisAnalysishelpshelpspreventpreventfaultsfaultsandandincidentsincidentsininfuturefuture

AnnouncingAnnouncingpotentialpotentialundesirableundesirableeffectseffectsbeforebeforelaunchinglaunchinganyanyhighhigh--riskriskactivitiesactivities

WhileWhileconductingconductingaapoll,poll,askaskyouryourcustomerscustomerswhatwhattheytheydon’tdon’tlikelikeininthethenewnewproductproduct
Strategies
Strategiesand Recommendationsand Recommendations
o
oIf your system or object is subjected to a certain action If your system or object is subjected to a certain action which produces both negative and positive effects on the which produces both negative and positive effects on the system or its system or its supersystemsupersystem, consider subjecting the system , consider subjecting the system to an antipodal (inverse) action beforehand, so that it will to an antipodal (inverse) action beforehand, so that it will compensate or eliminate the negative effect when the compensate or eliminate the negative effect when the negative effect occurs.negative effect occurs.
Examples
Examples((ITIT))

UseUseofofantivirusesantiviruses

MakingMakingdatadatabackupsbackupsforforaalaterlaterrecoveryrecoveryininemergencyemergencysituationssituations

ProjectProjectriskriskmanagementmanagement——revealingrevealingininadvanceadvanceanyanyundesirableundesirablesituationssituationsthatthatcouldcouldhappenhappenwithinwithinaaprojectprojectandandpreventingpreventingoccurrenceoccurrenceofofthosethosesituationssituationsduringduringthetheprojectprojectimplementationimplementation

HavingHavingwarningwarningmessagesmessagesdisplayeddisplayedbeforebeforeaauseruserexecutesexecutesananoperationoperationthatthatisispotentiallypotentiallydangerousdangerous
12
12
CONFIDENTIAL
CONFIDENTIAL
#10
#10::PRIOR ACTIONPRIOR ACTION
Examples
Examples((Business SystemsBusiness Systems))

The holding companyThe holding companystructure helps protect the structure helps protect the intellectual property from bankruptcyintellectual property from bankruptcy

Set Set the time of starting a meeting a few minutes before the the time of starting a meeting a few minutes before the requiredrequired

Before rolling a brand new product onto the market, make Before rolling a brand new product onto the market, make sure that customers understand the values this new product sure that customers understand the values this new product offers themoffers them

At Epson, the At Epson, the engineers that deal with the development of engineers that deal with the development of new products, follow the new products, follow the secondmentsecondmentsystem, also working system, also working as salespersons and maintenance specialistsas salespersons and maintenance specialists
Strategies
Strategiesand Recommendationsand Recommendations
o
oIf your system or process experiences harmful influence of If your system or process experiences harmful influence of its its supersystemsupersystem, create preliminary conditions that will , create preliminary conditions that will prevent the system from influence of those harmful prevent the system from influence of those harmful factors.factors.
o
oIf your system or process is going to be changed in a certain If your system or process is going to be changed in a certain moment of time but such a change is difficult to achieve moment of time but such a change is difficult to achieve exactly when needed, perform the required change of the exactly when needed, perform the required change of the system/object (fully or partially) in advance.system/object (fully or partially) in advance.
o
oPrearrange different parts of your system or process Prearrange different parts of your system or process activities in such a way that they can be “assembled” right activities in such a way that they can be “assembled” right where and when it becomes necessary but not before.where and when it becomes necessary but not before.
Examples
Examples((ITIT))

TheTheoptimizedoptimizeddatabasedatabasequeriesqueriesprovideprovideforforexecutionexecutionofofpreliminarypreliminaryproceduresprocedures

UseUseofofdefaultdefaultvalues,values,specifying,specifying,forforexample,example,disk,disk,directory,directory,language,language,andandotherother

CachingCaching——aaprocedureprocedureofofpreliminarypreliminaryaccumulationaccumulationofofdatadataforforsubsequentsubsequentoperations,operations,suchsuchasasaadiskdiskwritewriteorortransmissiontransmissionthroughthroughcommunicationcommunicationchannelschannels

UseUseofofkeykeywordswordstotoimproveimproveefficiencyefficiencyofofsearchsearchforforthetherequiredrequiredcontentcontent
13
13
CONFIDENTIAL
CONFIDENTIAL
#11
#11::BEFOREHAND CUSHIONINGBEFOREHAND CUSHIONING
Examples
Examples((Business SystemsBusiness Systems))

ServiceServicesupportsupportforforaanewnewproductproductisisdeployeddeployedpriorpriortotointroducingintroducingitittotothethemarketmarket

HoldingHoldingshortshortandandefficientefficient“no“no--chairs”chairs”meetingsmeetings

AddingAddingthethetermstermsofofarbitragearbitrageintointoaacontractcontracttotoavoidavoidanyanytrialtrialproceedingsproceedings

RiskRiskmanagementmanagementandandemergencyemergencyplanningplanning

InformingInformingcustomerscustomersononthethescheduledscheduledactivitiesactivitiespriorpriortotostartingstartingthetheservicingservicing
Strategies
Strategiesand Recommendationsand Recommendations
o
oCreate conditions in advance that will eliminate a chance Create conditions in advance that will eliminate a chance for a negative effect to happen.for a negative effect to happen.
o
oCreate conditions in advance that will immediately fix the Create conditions in advance that will immediately fix the negative effect if it happens.negative effect if it happens.
o
oCreate conditions in advance that will immediately Create conditions in advance that will immediately compensate for the negative effect.compensate for the negative effect.
Examples
Examples((ITIT))

SavingSavingdeleteddeletedfilesfilesininaa“basket”“basket”totoenableenabletheirtheirlaterlaterrecoveryrecovery

“Undo”“Undo”operationoperationthatthatallowsallowstotocancelcancelthetheoperationsoperationsexecutedexecutedbybymistakemistake

DataDatabackupbackupandandemergencyemergencyrecoveryrecovery

SwitchingSwitchingaasystemsystemintointothethehibernationhibernationmodemodetotosavesavepowerpowerwhenwhenthethesystemsystemhashasnotnotbeenbeenusedusedforforaacertaincertainperiodperiodofoftimetime

MirrorMirrordisksdisks//RAIDRAID//mirrormirrorserversservers
14
14
CONFIDENTIAL
CONFIDENTIAL
#12
#12::TENSION REMOVALTENSION REMOVAL
Examples
Examples((Business SystemsBusiness Systems))

“Horizontal”“Horizontal”careercareergrowthgrowthtotoexpandexpandcompetenciescompetencies

IncreasingIncreasingthethecustomers’customers’loyaltyloyaltybybyarrangingarrangingmeetings,meetings,events,events,andandinformationinformationsharingsharingwithwithcustomerscustomers

TeamTeammembersmembersdistributedistributebonuses,bonuses,awards,awards,andandbenefitsbenefitsonontheirtheirownown(managers(managersarearenotnotinvolved)involved)

HoldingHoldingaajobjobinterviewinterviewatataacafécafératherratherthanthanatatofficeoffice

InvolvingInvolvingaathirdthirdpartypartytotohelphelpresolveresolveconflictsconflicts
Strategies
Strategiesand Recommendationsand Recommendations
o
oCreate conditions to eliminate or compensate possible Create conditions to eliminate or compensate possible tension that occur or may occur within a system or tension that occur or may occur within a system or between a system and its between a system and its supersystemsupersystem..
o
oCreate conditions to eliminate or compensate possible Create conditions to eliminate or compensate possible tension that occur or may occur within a process or tension that occur or may occur within a process or between a process and its between a process and its supersystemsupersystem..
o
oIntegrate different objects or systems to remove tension.Integrate different objects or systems to remove tension.
o
oIntroduce a new object or a process activity to decrease Introduce a new object or a process activity to decrease possible tension.possible tension.
o
oEliminate or replace an object or process activity that Eliminate or replace an object or process activity that creates tension.creates tension.
o
oBreak a process to smaller steps to remove possible Break a process to smaller steps to remove possible tension.tension.
Examples
Examples((ITIT))

PresentingPresentingthetheoutputoutputdatadataininaaformatformatthatthatisismoremorefamiliarfamiliarandandconvenientconvenientforforusersusers

VirtualVirtualmemorymemoryallocationallocationdependingdependingononthetheavailableavailablefreefreephysicalphysicalmemorymemoryresourcesresources

SCADASCADA(Supervisory(SupervisoryControlControlandandDataDataAcquisition)Acquisition)developmentdevelopmentmethodologymethodology
15
15
CONFIDENTIAL
CONFIDENTIAL
#13
#13::OTHER WAY ROUNDOTHER WAY ROUND
Examples
Examples((Business SystemsBusiness Systems))

HomeHomeshopping,shopping,homehomebankingbankingserviceservice

ParkPark--andand--riderideschemesschemesininthethecitiescitieswithwithheavyheavytraffictraffic

MobileMobilemaintenancemaintenance——aamechanicmechaniccomescomestotoaaclientclientratherratherthanthanthetheclientclientcomescomestotoaagaragegarage..

TheTheadvertisingadvertisingslogansloganthatthatsayssays“Rolls“Rolls--RoyceRoyceisisthethemostmostexpensiveexpensiveandandthetheleastleasteconomicaleconomicalcarcarininthetheworld,”world,”attractsattractsrichrichbuyersbuyers..

BenchmarkingBenchmarkingagainstagainstthetheworstworstinsteadinsteadofofbenchmarkingbenchmarkingagainstagainstthethebestbest
Strategies
Strategiesand Recommendationsand Recommendations
o
oInstead of the required actions, consider performing an Instead of the required actions, consider performing an antipodal (inverse) action to achieve the desired positive antipodal (inverse) action to achieve the desired positive effect.effect.
o
oConsider replacing the parts of your system with the parts Consider replacing the parts of your system with the parts that have opposite (inverse) features: filled−hollow, that have opposite (inverse) features: filled−hollow, black−white, and so on.black−white, and so on.
o
oReverse the order of actions/activities.Reverse the order of actions/activities.
o
oMake the nonMake the non--dynamic part of your system dynamic or fix dynamic part of your system dynamic or fix the dynamic parts.the dynamic parts.
o
oTurn your object/system upside down.Turn your object/system upside down.
o
oInvert the entire process or some of the steps of the Invert the entire process or some of the steps of the process.process.
Examples
Examples((ITIT))

ReverseReverseengineeringengineering——recoveryrecoveryofoffunctionalfunctionalspecifications,specifications,protocols,protocols,andandformatsformatsthroughthroughdecompilingdecompilingofofthetheexecutableexecutablecodecode

AAbacktrackingbacktrackingmechanismmechanismininthethePrologProloglanguagelanguage

SavingSavingtransactionstransactionsininthethereversereverseorderorderforforaalaterlaterrollbackrollback((LastLastin,in,FFirstirstout)out)

UpsideUpside--downdownversioningversioning

TheTheInvertedInvertedPyramidPyramid——provisionprovisionofofinformationinformationbybyascendingascendingorordescendingdescendingprioritypriority
16
16
CONFIDENTIAL
CONFIDENTIAL
#14
#14::NONNON--LINEARITYLINEARITY
Examples
Examples((Business SystemsBusiness Systems))

RotationRotationofofteamteamleadersleaders

SupermarketsSupermarketswithwithaacircularcircularratherratherthanthanlinearlinearrowrowarrangementarrangement

OptimizationOptimizationofofthetheresourcesresourcesrequiredrequiredforforaaprocessprocessininaccordanceaccordancewithwithaanonlinearnonlinearfunctionfunction

AtAtLeviLeviStraussStrauss&&Co,Co,thetheITITdepartmentdepartmenthashasthetheorganizationalorganizationalstructurestructurelikelikethethesolarsolarsystemsystemstructurestructure::thethenamesnamesofof2020managersmanagersarearenotednotedonceonceininaabigbigcirclecircleandandonce,once,ininaasmallersmallercirclecircle..TheThesmallersmallercirclescirclesrepresentrepresentworkingworkinggroupsgroupsononspecificspecificissues,issues,includingincludingcustomercustomerservicesservicesandandbusinessbusinesssystemssystems..
Strategies
Strategiesand Recommendationsand Recommendations
o
oInstead of linear parts or structure of a system, consider Instead of linear parts or structure of a system, consider using “curved”, “spherical” parts or systems.using “curved”, “spherical” parts or systems.
o
oInstead of linear processes use nonlinear processes.Instead of linear processes use nonlinear processes.
o
oSequel linear and nonlinear parts within a process.Sequel linear and nonlinear parts within a process.
o
oIf a process is nonlinear, consider increasing the degree of If a process is nonlinear, consider increasing the degree of nonlinearity.nonlinearity.
o
oUse a circular flow instead of a linear flow.Use a circular flow instead of a linear flow.
o
oUse roundabout solutions in a process.Use roundabout solutions in a process.
Examples
Examples((ITIT))

Cycles,Cycles,recursiverecursivefunctionsfunctionsofofsoftwaresoftwareprogramsprograms

SpiralSpiraldevelopmentdevelopment——aasoftwaresoftwaredevelopmentdevelopmentmethodologymethodologywherewherethetheriskriskassessmentassessmentisisthetheprimaryprimarydriverdriverofoftasktaskselectionselection

TheThecycliccyclicscrollingscrollingofoflistlistelements,elements,forforexample,example,photos,photos,pictures,pictures,andandother,other,ononthethescreenscreen
17
17
CONFIDENTIAL
CONFIDENTIAL
#15
#15::DYNAMIZATIONDYNAMIZATION
Examples
Examples((Business SystemsBusiness Systems))

Using a flexible (mobile) rather than a static hierarchical Using a flexible (mobile) rather than a static hierarchical organizational structureorganizational structure

Continuous improvement of processesContinuous improvement of processes

Continuous trainingContinuous training

CaseCase--specific dynamic adjustment of processesspecific dynamic adjustment of processes

FurnitureFurnitureonline shoppingonline shopping——a customer can control camera a customer can control camera motion to examine individual elements of the interiormotion to examine individual elements of the interior
Strategies
Strategiesand Recommendationsand Recommendations
o
oIf your system is static and immobile, make it dynamic and If your system is static and immobile, make it dynamic and movable.movable.
o
oDivide your system into the parts capable of moving Divide your system into the parts capable of moving relatively to each other.relatively to each other.
o
oIncrease the degree of free motion within your system.Increase the degree of free motion within your system.
o
oMake your object or its nearest Make your object or its nearest supersystemsupersystemdynamically dynamically change and adapt in accordance with the required change and adapt in accordance with the required conditions at each stage of operation.conditions at each stage of operation.
o
oMake the structure of your process more dynamic.Make the structure of your process more dynamic.
o
oIncrease the degree of dynamics of those process activities Increase the degree of dynamics of those process activities that experience negative influence of that experience negative influence of supersystemsupersystemor which or which performance has to be increased.performance has to be increased.
Examples
Examples((ITIT))

DDLDDL((Dynamic Linked LibrariesDynamic Linked Libraries))——a set of functions that are a set of functions that are notnotintegral to an app but can be loaded and used by the integral to an app but can be loaded and used by the appapp

DHTMLDHTML//Active Server PagesActive Server Pages——dynamically created webdynamically created web--pages instead of staticpages instead of staticwebweb--pagespages

Enabling users to configureEnabling users to configuretoolbars and interface layout in toolbars and interface layout in appsapps

ScreenScreenor page cor page custom settingsustom settingson a smartphone or tableton a smartphone or tablet
18
18
CONFIDENTIAL
CONFIDENTIAL
#16
#16::SLIGHTLY LESS OR MORESLIGHTLY LESS OR MORE
Examples
Examples((Business SystemsBusiness Systems))

KeepKeepcontactscontactslongerlongerthanthanrequiredrequired

BeBefocusedfocusedonongettinggettingyouryourcustomerscustomersamazedamazedratherratherthanthanjustjustmeetingmeetingtheirtheirneedsneeds

ProvidingProvidingaauseruserwithwithseveralseveralelectronicelectronicdevicesdevicesforfortestingtestingatathomehomeandandmakingmakingaachoicechoice

IfIfsomesomeprocessprocesshashasaacriticalcriticalstage,stage,allocateallocatemoremoreresourcesresourcesforforthisthisstagestagetotopreventpreventgapsgaps

WhenWhenenteringenteringaanewnewmarket,market,conductconductananaggressiveaggressiveadvertisingadvertisingcampaigncampaignininallallpossiblepossiblemediamedia::mailingmailinglists,lists,newspapers,newspapers,magazines,magazines,radio,radio,television,television,billboards,billboards,etcetc..
Strategies
Strategiesand Recommendationsand Recommendations
o
oIf the required change of your system or your process If the required change of your system or your process cannot be achieved precisely, or the desired goal cannot be cannot be achieved precisely, or the desired goal cannot be achieved in full, then reformulate the problem:achieved in full, then reformulate the problem:
•
•How to make or deliver slightly less and then achieve How to make or deliver slightly less and then achieve the required effect.the required effect.
•
•Make or deliver slightly more to achieve the required Make or deliver slightly more to achieve the required effect.effect.
Examples
Examples((ITIT))

StressStress--testingtestingprovidesprovidescheckingcheckingananapplication’sapplication’sbehaviorbehaviorunderunderananexcessexcessload,load,forforexample,example,withwithaabigbignumbernumberofoftransactionstransactionsororsimultaneouslysimultaneouslyopenedopenedsessionssessions

UpdatingUpdatingananapplicationapplicationbybypatchespatchesandandserviceservicepackspacksinsteadinsteadofofitsitsfullfullreplacementreplacement

AutomaticAutomaticwindowwindowresizingresizingwhenwhenthethescreenscreenresolutionresolutionchangeschanges
19
19
CONFIDENTIAL
CONFIDENTIAL
#17
#17::ANOTHER DIMENSIONANOTHER DIMENSION
Examples
Examples((Business SystemsBusiness Systems))

ChangingChangingorientationorientationfromfromthethe“linear”“linear”toto“project”“project”managementmanagementininaamatrixmatrixorganizationorganization

IntegrationIntegrationofofaanewnewvaluevalue--addedaddeddimensiondimensionininthethesuppliersupplier--customercustomerrelationshiprelationship

MultiMulti--levellevelstoragestoragesystemssystemsallowallowusingusingthetheheightheightofofaabuildingbuildingandandsavingsavingthethefloorfloorareaarea

HorizontalHorizontal((peerpeer22peer)peer)communicationscommunications

ExaminingExaminingthethesituationsituationininananorganizationorganizationfromfromthetheoutsideoutside——eithereitherdirectlydirectlyororbybyinvolvinginvolvingconsultants,consultants,hiredhiredbuyers,buyers,etcetc..
Strategies
Strategiesand Recommendationsand Recommendations
o
oUse other dimensions, in addition to the already used ones, Use other dimensions, in addition to the already used ones, in your system or your process.in your system or your process.
o
oIntroduce a new dimension to your system, process, or Introduce a new dimension to your system, process, or their their supersystemsupersystem..
o
oUse a multiUse a multi--layered arrangement instead of a singlelayered arrangement instead of a single--layer layer one for a system or a process.one for a system or a process.
o
oTilt or reorient the system in space.Tilt or reorient the system in space.
o
oIntroduce viewing of your system or process at a different Introduce viewing of your system or process at a different angle.angle.
Examples
Examples((ITIT))

OnlineOnlineAnalyticalAnalyticalProcessingProcessing((OLAPOLAP))——aatechnologytechnologyforformultidimensionalmultidimensionaldatadataprocessingprocessing

ResizingResizingofofthetheinterfaceinterfaceobjectsobjectswhenwhenaasmartphonesmartphoneisistiltedtilted

TheThespiralspiralmethodologymethodologyofofsoftwaresoftwaredevelopmentdevelopment——aaseriesseriesofofiterationsiterationswithinwithinaawaterfallwaterfallmodel,model,ininwhichwhichoneoneororseveralseveralsystemsystemparametersparametersareareimprovedimprovedatateacheachiterationiteration

UsingUsingvoxelsvoxelsinsteadinsteadofofpixelspixelsininthethe33DD--designdesignsystemssystems
20
20
CONFIDENTIAL
CONFIDENTIAL
#18
#18::RESONANCE (COORDINATION)RESONANCE (COORDINATION)
Examples
Examples((Business SystemsBusiness Systems))

A campaign on promotion of insurances for the travels A campaign on promotion of insurances for the travels during the holiday and vacation seasonsduring the holiday and vacation seasons

Offering customersOffering customerssome some extraextraservices during the product services during the product salessales

Augmenting the stock of vacation goods for the period ofAugmenting the stock of vacation goods for the period ofholidays and vacationsholidays and vacations

An electronic billboardAn electronic billboardwhere advertisements are changed where advertisements are changed depending on the time of the daydepending on the time of the day

““KanceiKancei””——a Japanese terma Japanese termthat describes the productthat describes the product--customer resonance situationcustomer resonance situation
Strategies
Strategiesand Recommendationsand Recommendations
o
oMake your system “vibrate”.Make your system “vibrate”.
o
oMake actions produced by your system match the actions of Make actions produced by your system match the actions of another system to achieve an optimal running or a another system to achieve an optimal running or a synergetic effect.synergetic effect.
o
oMatch the periodicity of the actions/activities produced by Match the periodicity of the actions/activities produced by two different systems or processes.two different systems or processes.
o
oMatch intervals of actions produced by two systems or Match intervals of actions produced by two systems or processes.processes.
o
oMatch in space or in shape two systems that interact with Match in space or in shape two systems that interact with each other.each other.
Examples
Examples((ITIT))

A vibrating message that attracts aA vibrating message that attracts auser’s attentionuser’s attention

Find the “resonance” frequencyFind the “resonance” frequencyof the development team of the development team and use it to manage the team’s workand use it to manage the team’s work

To attract attention, change pictures on the screen with To attract attention, change pictures on the screen with the frequency that resonates with the human eyethe frequency that resonates with the human eye
21
21
CONFIDENTIAL
CONFIDENTIAL
#19
#19::PERIODIC ACTIONPERIODIC ACTION
Examples
Examples((Business SystemsBusiness Systems))

InsteadInsteadofofaacontinuouscontinuousexecutionexecutionofofaatask,task,setsettimetimelimitslimitsandandexecuteexecutethethetasktaskperiodicallyperiodically

IncreasingIncreasingthethetimetimeperperpatientpatientininprivateprivateclinicsclinicshelpshelpsavoidavoidmanymanyissuesissuesandandraiseraiseprofitsprofits

TheThetidaltidalschemesschemeshelphelpregulateregulatetraffictrafficininthetheareasareaswithwithheavyheavytraffictrafficconditionsconditions

ConductingConductingmaintenancemaintenanceworksworksduringduringthethevacationvacationandandholidayholidayperiodperiod
Strategies
Strategiesand Recommendationsand Recommendations
o
oInstead of a continuous process, use periodic or “pulsed” Instead of a continuous process, use periodic or “pulsed” actions.actions.
o
oIntroduce diversification among time intervals between the Introduce diversification among time intervals between the actions, depending on the operating conditions or changes actions, depending on the operating conditions or changes in the in the supersystemsupersystem..
o
oDynamically vary periodicity of process actions according to Dynamically vary periodicity of process actions according to the operating conditions or changes in the system or the operating conditions or changes in the system or supersystemsupersystem..
o
oUse the available pauses between process actions to Use the available pauses between process actions to perform some other useful process action(s).perform some other useful process action(s).
Examples
Examples((ITIT))

TimerTimer--controlledcontrolledbackupbackup——automaticautomaticbackupbackupatatthethespecifiedspecifiedtime,time,forforexample,example,atatnightnight

GarbageGarbageCollectionCollection——aaregularregularprocessprocesstotounallocateunallocatethetheunusedunusedmemorymemoryresourcesresources

RegularRegularpingingpingingtotopreventpreventthethesystemsystemfromfromswitchingswitchingtotothethe“sleep”“sleep”modemode

RegularRegularcheckingcheckingforforupdatesupdates

SettingSettingprioritiesprioritiesforfortaskstasksororprocessesprocessesininthetheoperatingoperatingsystemsystem
22
22
CONFIDENTIAL
CONFIDENTIAL
#20
#20::ACTION CONTINUITYACTION CONTINUITY
Examples
Examples((Business SystemsBusiness Systems))

ContinuousContinuousmonitoringmonitoringoveroveroperationoperationofofthetheOtisOtiselevatorselevators——fullfullsupportsupport

2424//77hothotlineline

UseUseofofcoffeecoffeebreaksbreakstotodiscussdiscusscurrentcurrentissuesissuesandandformulateformulatenewnewideasideas

AccessAccesstotothetheInternetInternetinintrainstrainsandandplanesplanes

ContinuousContinuoustrainingtrainingphilosophyphilosophy

WiWi--MaxMax::continuouscontinuousInternetInternetaccessaccess

“Turnover”“Turnover”creditscreditsfromfromVisaVisaandandMastercardMastercard

2424//77hotelhotelserviceservice
Strategies
Strategiesand Recommendationsand Recommendations
o
oMake all processes in your system work continuously.Make all processes in your system work continuously.
o
oEliminate all idle running from your process.Eliminate all idle running from your process.
o
oIf it is not possible to avoid idle pauses in your process, If it is not possible to avoid idle pauses in your process, consider filling them with some other positive process consider filling them with some other positive process activities.activities.
Examples
Examples((ITIT))

PrintingPrintingduringduringaacarriagecarriage--returnreturnmovementmovementininthethedotdot--matrixmatrixprintersprinters

PhysicalPhysicallocationlocationofofimportantimportantelementselementsofofnetworknetworkininspecificspecificplacesplacestotomakemaketheirtheiroperationoperationefficientefficient

SyncingSyncingofofthethereadreadandandwritewriteoperationsoperationsinindatabasesdatabases
23
23
CONFIDENTIAL
CONFIDENTIAL
#21
#21::HIGH SPEEDHIGH SPEED
Examples
Examples((Business SystemsBusiness Systems))

FastFastCycle−FullCycle−FullParticipationParticipation——aamethodmethodofofinvolvinginvolvingthethewholewholeorganizationorganizationintointothethereorganizationreorganizationprocessesprocesses

FastFastDesignDesignpermitspermitsassessassessthetheoutcomeoutcomepriorpriortototakingtakingaadecisiondecision

ExpressExpress--trainingtraininginsteadinsteadofoflonglongclassesclasses

“Fast“Fastandanddirty”dirty”——aaprototypeprototypetechniquetechniquethatthatprovidesprovidesfastfastmakingmakingofofaaprototypeprototypeandandestimatingestimatingthethecustomers’customers’responseresponse
Strategies
Strategiesand Recommendationsand Recommendations
o
oIf your system/object is subjected to harmful or hazardous If your system/object is subjected to harmful or hazardous actions within some process, perform the required process actions within some process, perform the required process at a very high speed.at a very high speed.
o
oIf your process experiences harmful effects caused by the If your process experiences harmful effects caused by the environment, conduct the process at a high speed.environment, conduct the process at a high speed.
o
oIf it is difficult to perform some change of your system due If it is difficult to perform some change of your system due to emergence of negative effects during the process of to emergence of negative effects during the process of change, perform the required change at a very high speed.change, perform the required change at a very high speed.
o
oIncrease the speed of the process that causes harmful Increase the speed of the process that causes harmful effects.effects.
o
oLocate the activity within a process that might cause a Locate the activity within a process that might cause a negative effect and conduct this activity at a high speed.negative effect and conduct this activity at a high speed.
Examples
Examples((ITIT))

GRIDGRIDcomputingcomputing——componentscomponentsofofaahighhigh--speedspeednetworknetworkcomputingcomputing

RandomRandombackupbackupinsteadinsteadofofaafullfullbackupbackup
24
24
CONFIDENTIAL
CONFIDENTIAL
#22
#22::BLESSING IN DISGUISEBLESSING IN DISGUISE
Examples
Examples((Business SystemsBusiness Systems))

RelocateRelocateaa“problem”“problem”employeeemployeetotoaapositionpositionwherewherethetheemployeeemployeecouldcouldbenefitbenefitthethecompanycompanyandandwouldwouldnotnotdisturbdisturbthetheformerformercoworkerscoworkers

CollectingCollectingthetheusers’users’claimsclaimshelpshelpsimproveimprovethetheproductproduct

IfIfthethegoodsgoodscannotcannotbebedelivereddeliveredonontime,time,limitlimittheirtheirsupplysupplyupuptotocreatingcreatingaashortageshortageofofgoodsgoods

MakingMakingthetheparkingparkinglotslotsexpensiveexpensiveininthethecitycityandandcheapercheaperininsuburbssuburbshelpshelpsmovemovethethetraffictrafficoutoutofofthethecitycityboundariesboundaries
Strategies
Strategiesand Recommendationsand Recommendations
o
oUse harmful factors or negative effects that arise in your Use harmful factors or negative effects that arise in your system, your process or their system, your process or their supersystemsupersystemto achieve to achieve positive results.positive results.
o
oEliminate a harmful factor by adding it to another harmful Eliminate a harmful factor by adding it to another harmful factor.factor.
o
oAmplify the harmful factor to such a degree that it would Amplify the harmful factor to such a degree that it would stop bringing harm to your system or its stop bringing harm to your system or its supersystemsupersystem..
Examples
Examples((ITIT))

UseUseofoffreefreecomputercomputerresourcesresourcesforforthetheexecutionexecutionofof“heavy”“heavy”backgroundbackgroundprocessesprocesses

UseUseofofaafreefreecomputercomputerresourceresourceforforthethenetworknetworkcomputingcomputing

SynchronousSynchronousmirroringmirroring::afterafteraawritewriteoperationoperationininthetheprimaryprimarysystemsystemisisexecuted,executed,thetheoperationoperationisismirroredmirroredininthethesecondarysecondarysystemsystem..
25
25
CONFIDENTIAL
CONFIDENTIAL
#23
#23::FEEDBACKFEEDBACK
Examples
Examples((Business SystemsBusiness Systems))

InteractiveInteractiveinformationinformationee--boardsboardsforforconsumersconsumers

ConductingConductingmarketingmarketingsurveyssurveystogethertogetherwithwithusersusers((AmazonAmazon..comcom))

TheTheintroductionintroductionofofnewnewfreefreeservicesserviceshelpshelpsencourageencourageusersuserstotoprovideprovidefeedbackfeedback

RFIDRFIDmarksmarkshelphelptracktrackthethemovementmovementofofgoodsgoods

BlogsBlogshelphelpcompaniescompaniesgetgetfeedbackfeedbackfromfromconsumersconsumers
Strategies
Strategiesand Recommendationsand Recommendations
o
oIntegrate feedback into your system or between your Integrate feedback into your system or between your system and its system and its supersystemsupersystem..
o
oIf feedback is available but is not effective enough, If feedback is available but is not effective enough, consider making it dynamic by varying the feedback consider making it dynamic by varying the feedback components and structure in accordance with the operating components and structure in accordance with the operating conditions.conditions.
o
oIf it is known that a negative effect can occur, consider If it is known that a negative effect can occur, consider creating the conditions that can initiate a negative creating the conditions that can initiate a negative feedback loop directed toward eliminating this negative feedback loop directed toward eliminating this negative effect or reducing its harmful consequences.effect or reducing its harmful consequences.
o
oIncrease the magnitude and scale of the existing feedback.Increase the magnitude and scale of the existing feedback.
Examples
Examples((ITIT))

AnAnautomaticautomaticfeedbackfeedbackmechanismmechanismininthethenetworksnetworkswherewherethetheloadloadrateratedynamicallydynamicallychangeschanges

UseUseofoftesttestpacketspacketsinindatadatatransmissiontransmission

ChangingChangingthetheresponseresponseparametersparametersofofinterfaceinterfaceelementselementsaccordingaccordingtotoaauser’suser’sbehaviorbehaviorandandthetheconditionsconditionsofofuseuse

UseUseofofthetheInternetInternettraffictrafficautomaticautomatictrackingtrackingsystemssystemshelpshelpscollectcollectinformationinformationaboutaboutusersusers
26
26
CONFIDENTIAL
CONFIDENTIAL
#24
#24::INTERMEDIARYINTERMEDIARY
Examples
Examples((Business SystemsBusiness Systems))

CompaniesCompaniesinviteinvitefamousfamousandandpopularpopularpeoplepeopletotoadvertiseadvertisenewnewbulkbulkproductsproducts

KLMKLMairlinesairlinesfollowsfollowsthetheconceptconceptthatthatshortshortflightsflightsfromfromGermanyGermanyandandthetheUKUKtotoHollandHollandallowallowpassengerspassengerstotoconductconductlonglongflightsflightsfromfromHollandHolland

InvolvingInvolvingaamediatormediator(the(thethirdthirdparty)party)totosettlesettledisputesdisputesbetweenbetweencompaniescompanies

InvolvingInvolvingextraextrapersonnelpersonnelforforthethepeakpeakperiodsperiodsofofworkwork
Strategies
Strategiesand Recommendationsand Recommendations
o
oUse an intermediate carrier to provide necessary Use an intermediate carrier to provide necessary functionality or to eliminate the negative effects while functionality or to eliminate the negative effects while preserving the positive effects.preserving the positive effects.
o
oCheck if available resources can act as an intermediary Check if available resources can act as an intermediary object.object.
o
oTemporarily merge your object/system with a foreign Temporarily merge your object/system with a foreign object/system that will provide the required action and object/system that will provide the required action and then, if necessary, remove (eliminate) the foreign then, if necessary, remove (eliminate) the foreign system/object.system/object.
o
oTemporarily merge your process with a foreign process that Temporarily merge your process with a foreign process that will provide the required action.will provide the required action.
o
oIntroduce a new intermediary object/system, which is a Introduce a new intermediary object/system, which is a modification of the first or the second object (system), if a modification of the first or the second object (system), if a problem relates to the interaction between the two problem relates to the interaction between the two systems. The modification should be understood in a broad systems. The modification should be understood in a broad sense: as a material, property, energy, or any other type of sense: as a material, property, energy, or any other type of modification.modification.
Examples
Examples((ITIT))

AAdatadataintegrationintegrationsystemsystem——ActiveActiveMediatorMediatorObjectObjectSystemSystem((AMOSAMOS))——isisbasedbasedononthetheuseuseofofaamediatormediator

CompilingCompilingtotoananintermediaryintermediaryformatformatsuchsuchasasMSILMSILinin..NETNETororthethebytecodebytecodeininJavaJava

UsingUsingAPIAPI(Application(ApplicationProgrammingProgrammingInterface)Interface)forforapplicationapplicationintegrationintegration

ODBCODBC(Open(OpenDataDataBaseBaseConnectivity)Connectivity)

CreationCreationofoftemporarytemporaryfilesfilesduringduringananappappexecutionexecution
27
27
CONFIDENTIAL
CONFIDENTIAL
#25
#25::SELFSELF--SERVICESERVICE
Examples
Examples((Business SystemsBusiness Systems))

SelfSelf--supportingsupportingbrand,brand,suchsuchasasHarvardHarvardBusinessBusinessSchoolSchool——itsitsgraduatesgraduatesareareoutstandingoutstandingpeoplepeoplewhowhomakemakereputationreputationofofthetheschoolschoolhigherhigher;;thisthisencouragesencouragesmoremorepeoplepeopletotoenrollenrollatatthetheschool,school,andandthereforethereforethetheschoolschoolisisableabletotoselectselectthethebestbest

OfferOfferdiscountsdiscountstotothethecustomerscustomerswhowhoprovideprovidefeedbackfeedbackononthetheproductsproducts

IndustrialIndustrialecoeco--systemssystems——thethefactoriesfactoriesthatthatuseuseheatingheatingsystemsystemwastewasteproductsproductstotoperformperformotherotheroperations,operations,forforexample,example,bybyusingusingthetheheatheattransfertransferwaterwaterrepeatedlyrepeatedlyininvariousvariousprocesses,processes,andandsosoonon
Strategies
Strategiesand Recommendationsand Recommendations
o
oThe object/system must serve itself by performing tuning, The object/system must serve itself by performing tuning, adjusting, and repair operations all by itself.adjusting, and repair operations all by itself.
o
oUse available resources or waste resources within your Use available resources or waste resources within your system to achieve the required degree of selfsystem to achieve the required degree of self--service.service.
o
oUse available resources or waste resources within the Use available resources or waste resources within the environment of your system to achieve the desired degree environment of your system to achieve the desired degree of selfof self--service.service.
o
oConsider using already available activities in your process Consider using already available activities in your process to service other activities.to service other activities.
Examples
Examples((ITIT))

SoftwareSoftwareUpdateUpdateChannelsChannels——automaticautomaticupdatesupdatesofofsoftwaresoftware

SelfSelf--learninglearningadaptiveadaptivealgorithmsalgorithms

SelfSelf--mergemergeinindatabasesdatabases

AutoAutoSaveSave——regularregularsavingsavingofofchangeschangesmademadebybyaauseruser

SelfSelf--protectionprotectionmodemodeininantivirusantivirussoftwaresoftware

OnlineOnlineupdateupdate——checkingcheckingforfornewnewupdatesupdatesandandautomaticautomaticupdateupdateinstallationinstallation
28
28
CONFIDENTIAL
CONFIDENTIAL
#26
#26::USE OF COPIES AND MODELSUSE OF COPIES AND MODELS
Examples
Examples((Business SystemsBusiness Systems))

CarryingCarryingoutoutaaconsumerconsumerresponseresponsesurveysurveyusingusingaamodelmodelororprototypeprototypeofofthetheproductproduct

BusinessBusiness--processprocesssimulationsimulationhelpshelpsfindfindoutoutdiscrepanciesdiscrepanciesininprocessesprocesses

UseUse--casecasescenarioscenariosimulationsimulationhelpshelpsdrawdrawpositivepositivescenariosscenariosforforentryentrytotothethemarketmarket

SingleSingle--useuseorganizationalorganizationalstructuresstructuresatatthethefastfastevolvingevolvingmarketsmarkets

FlightFlightsimulatorssimulatorshelphelpreducereducepilotpilottrainingtrainingcostscosts
Strategies
Strategiesand Recommendationsand Recommendations
o
oIf you need to undertake certain actions that may damage a If you need to undertake certain actions that may damage a fragile or expensive system/object, use its simpler and fragile or expensive system/object, use its simpler and cheaper copy.cheaper copy.
o
oIf you need to undertake certain actions with respect to If you need to undertake certain actions with respect to unavailable, complex, expensive, or dangerous object, use unavailable, complex, expensive, or dangerous object, use its copy instead.its copy instead.
o
oIf the If the required required process is too complex and risky, use a process is too complex and risky, use a simplified version of the process to run experiments.simplified version of the process to run experiments.
o
oInstead of a real physical system/object, use their “virtual” Instead of a real physical system/object, use their “virtual” copies (images, holograms).copies (images, holograms).
o
oUse virtual models of your systems.Use virtual models of your systems.
o
oBefore launching a complex process, experiment with its Before launching a complex process, experiment with its simpler “copies”.simpler “copies”.
Examples
Examples((ITIT))

CopyingCopyingtablestablesandandqueriesqueriesbetweenbetweendatadatasourcessourcesinsteadinsteadofofcreatingcreatingthemthemfromfromscratchscratch

UsingUsingbackgroundbackgroundimagesimagesandandheadersheadersororfooters,footers,whichwhicharearerepeatedrepeatedononeveryeverypagepageofofaadocumentdocument

CreationCreationofofthetheobjectsobjectsthatthatareareblueblue--printsprintsforforclassesclasses

LoadingLoadingwebweb--pagespagesfromfromaacachecacheororproxyproxy--serverserver..((BrowserBrowsersavessaveslocallocalcopiescopiesofofwebweb--pagespagesforforaasetsetperiodperiodofoftimetimetotoloadloadthosethosepagespagesfromfrommemorymemoryratherratherthanthandownloaddownloadthemthemfromfromaaremoteremoteserverserver..))
29
29
CONFIDENTIAL
CONFIDENTIAL
#27
#27::CHEAP AND SHORT LIFECHEAP AND SHORT LIFE
Examples
Examples((Business SystemsBusiness Systems))

SingleSingle--useuseorganizationalorganizationalstructuresstructuresatatthethefastfastevolvingevolvingmarketsmarkets

TheTheadvertisingadvertisingslogansloganbybySwatchSwatch::“Changing“Changingsuit?suit?ChangeChangeyouryourSwatchSwatch..””

SingleSingle--useuseorordisposabledisposablecameras,cameras,mobilemobilephones,phones,etcetc..

AAmultitudemultitudeofofcheapcheapadvertisingadvertisingcampaignscampaignsinsteadinsteadofofaalargelarge--scalescaleexpensiveexpensivecampaigncampaign

HiringHiringstudentsstudentsforforthethejobsjobsthatthatdodonotnotrequirerequirehighhighprofessionalprofessionalskillsskills
Strategies
Strategiesand Recommendationsand Recommendations
o
oReplace an expensive object/system with a number of Replace an expensive object/system with a number of cheaper ones.cheaper ones.
o
oInstead of a long, continuous, and expensive process, use a Instead of a long, continuous, and expensive process, use a number of shortnumber of short--term inexpensive activities.term inexpensive activities.
Examples
Examples((ITIT))

UseUseofoftemporarytemporaryfilesfilesratherratherthanthanarraysarraysororlargelargevariablesvariablestotostorestoretemporarytemporarydatadata

UseUseofofvirtualvirtualmemorymemoryononhardharddrivesdrives

VirtualVirtualdisksdisks

AAtrialtrialversionversion((3030daysdaysvalidvalid))ofofananapplicationapplication

TheThedevelopmentdevelopmentofofaafullfullversionversionofofananappappisiscostly,costly,sosoemployemployaafastfastprototypeprototype--makingmakingprocessprocessinstead,instead,quicklyquicklyproducingproducingthetheapplicationapplicationprototypesprototypeswhichwhichmeetmeetmajormajorrequirementsrequirements
30
30
CONFIDENTIAL
CONFIDENTIAL
#28
#28::PRINCIPLE REPLACEMENTPRINCIPLE REPLACEMENT
Examples
Examples((Business SystemsBusiness Systems))

PlasticPlasticcreditcreditcardscardsinsteadinsteadofofpaperpapermoneymoney

PaymentsPaymentsthroughthroughmobilemobilephonesphonesinsteadinsteadofofcreditcreditcardscards

InvolvingInvolvingresearchersresearcherstotoconductconductmarketmarketanalysisanalysisandandsearchsearchforfornewnewideasideas

33ММ::AskAskusersuserstotoproposeproposeinnovativeinnovativedecisionsdecisionsforforyouryourproductsproducts

CEOCEOChangeChange::aanewnewstrategicstrategicdecisiondecisionmodellingmodellingbybytransferringtransferringthetheCEOCEOfunctionsfunctionstotootherothermanagersmanagers
Strategies
Strategiesand Recommendationsand Recommendations
o
oIf a system or some its part cannot deliver its function with If a system or some its part cannot deliver its function with the required degree of performance or accuracy, consider the required degree of performance or accuracy, consider replacing the system or its part with another one based on replacing the system or its part with another one based on a different principle which is capable of delivering the a different principle which is capable of delivering the required function or performance.required function or performance.
o
oSometimes, in business systems it is sufficient to replace a Sometimes, in business systems it is sufficient to replace a basic operating principle behind the existing system part or basic operating principle behind the existing system part or a process activity it delivers without replacing that part.a process activity it delivers without replacing that part.
o
oAdd a new subsystem to your system that will deliver the Add a new subsystem to your system that will deliver the required functionality based on a new principle.required functionality based on a new principle.
o
oCheck if your system, process or Check if your system, process or supersystemsupersystemalready has a already has a component that meets the new required principle and use component that meets the new required principle and use it to achieve the needed functionality.it to achieve the needed functionality.
Examples
Examples((ITIT))

UseUseofofDDLDDL((DataDataDefinitionDefinitionLanguageLanguage))andandDMLDML((DataDataManipulationManipulationLanguageLanguage))insteadinsteadofofaaUIUIdatabasedatabaseandandviceviceversaversa

EncodingEncoding——aamethodmethodofofsavingsavingimportantimportantinformationinformationbybymakingmakingititunreadableunreadable

UsingUsingaaspeechspeechrecognitionrecognitionsystemsysteminsteadinsteadofofmanualmanualtexttexttypingtyping

BluetoothBluetooth

Chemical,Chemical,molecular,molecular,analogous,analogous,andandquantumquantumcomputerscomputers
31
31
CONFIDENTIAL
CONFIDENTIAL
#29
#29::FLUIDITYFLUIDITY
Examples
Examples((Business SystemsBusiness Systems))

FlexibleFlexible(fluid)(fluid)organizationalorganizationalstructuresstructuresinsteadinsteadofofoldoldstaticstatichierarchicalhierarchicalstructuresstructures

ApplyingApplyingthethe“probability”“probability”logiclogicinindecisiondecision--makingmakingprocessprocess

TheTheentitiesentitiesthatthatarearetraditionaltraditionalrivalsrivalscancancooperatecooperatewithinwithinsomesomeprojectsprojects

EstablishingEstablishingaaflexibleflexibleschedulescheduleofofcommunicationcommunicationwithwithusersusers

AAserviceservicestructurestructurethatthatcancanbebeadaptedadaptedpromptlypromptlytotoconsumers’consumers’needsneeds
Strategies
Strategiesand Recommendationsand Recommendations
o
oIncrease the “fluidity” of your system. Make the “solid” Increase the “fluidity” of your system. Make the “solid” parts “fluid” (with a high degree of freedom), or make parts “fluid” (with a high degree of freedom), or make some components capable of “flowing” through your some components capable of “flowing” through your system.system.
o
oFluidity means the increased degree of freedom (flexibility) Fluidity means the increased degree of freedom (flexibility) of components, of which the system is comprised.of components, of which the system is comprised.
o
oFluidity can be achieved by a multitude of smaller “nonFluidity can be achieved by a multitude of smaller “non--fluid” components acting together in a “fluid” way.fluid” components acting together in a “fluid” way.
Examples
Examples((ITIT))

StreamStreamprocessingprocessingofofdatadata

Dynamical,Dynamical,streamstream--orientedorientedcommunicationcommunicationbetweenbetweenentitiesentities
32
32
CONFIDENTIAL
CONFIDENTIAL
#30
#30::THIN AND FLEXIBLE SHELLSTHIN AND FLEXIBLE SHELLS
Examples
Examples((Business SystemsBusiness Systems))

CreditCreditcardcardtransactionstransactionsinsteadinsteadofofmoneymoneypaymentspayments

OfficeOfficeworkersworkerscancanuseusemovablemovablewallswallstotosetsetworkingworkingzoneszonesininopenopen--planplanofficesoffices

UsingUsingthethe“trade“tradesecret”secret”approachapproachforforseparatingseparatingimportantimportantbusinessbusinessinformationinformationfromfromgeneralgeneralknowledgebaseknowledgebaseininaacompanycompany

UseUseofofbubblebubblewrappingwrappingplasticplasticforfortransportationtransportationofoffragilefragilegoodsgoods
Strategies
Strategiesand Recommendationsand Recommendations
o
oUse “thin layers” to isolate a system or its part from the Use “thin layers” to isolate a system or its part from the supersystemsupersystem..
o
oInstead of impairing a feature to the whole system, impair Instead of impairing a feature to the whole system, impair the feature to its interface layer only.the feature to its interface layer only.
o
oUse flexible thin layers as a “coating” to add the required Use flexible thin layers as a “coating” to add the required functions or properties to your objects or system.functions or properties to your objects or system.
o
oInstead of complex and massive threeInstead of complex and massive three--dimensional physical dimensional physical structures usestructures useflexible shells and thin structures thatflexible shells and thin structures thatcan can be hollow inside.be hollow inside.
o
oIntroduce “thin barriers” to separateIntroduce “thin barriers” to separatebetween process between process activities.activities.
Examples
Examples((ITIT))

IncreasingIncreasingthethespeedspeedofofaauseruserserviceservicebybyusingusingaasinglesingleagentagentthatthatsuppliessuppliesallallnecessarynecessarydatadataininsuchsuchaawaywaythatthataauseruserdealsdealswithwithonlyonlyoneonecustomizablecustomizableinterfaceinterface..

TheThehyperbolichyperbolicbrowserbrowserplacesplacesobjectsobjectsononaahyperbolichyperbolicsurfacesurfaceratherratherthanthanononaaplaneplane..

AnAnadapteradapter((ororaawrapperwrapper))protectsprotectsananobjectobjectfromfromexternalexternalenvironmentenvironmentprovidingprovidingaafixedfixedinterfaceinterfacebetweenbetweenananinternalinternalobjectobjectandandthetheexternalexternalmediummedium..
33
33
CONFIDENTIAL
CONFIDENTIAL
#31
#31::HOLES AND NETWORKSHOLES AND NETWORKS
Examples
Examples((Business SystemsBusiness Systems))

RegardRegardthethelevel,level,ononwhichwhichyouryourcompanycompanyinteractsinteractswithwithcustomers,customers,asasaaporousporousmembranemembranethatthatfiltersfiltersthetheinformationinformationflowingflowingininandandoutoutthethecompanycompany..

CreateCreateaanetworknetworkofofusersusersandandletletthemtheminteractinteractonontheirtheirown,own,independentlyindependentlyfromfromyouyou..

ReinforceReinforceinternalinternalcommunicationscommunicationsatatallallmanagementmanagementlevelslevelsthroughthroughuseuseofofthetheInternetInternet;;provideprovideemployeesemployeesaccessaccesstotoCEOCEOandandviceviceversaversa..

MatrixMatrix--typetypeorganizationsorganizations
Strategies
Strategiesand Recommendationsand Recommendations
o
oMake your system “porous” by introducing “holes”.Make your system “porous” by introducing “holes”.
o
oIf the system is porous, fill the pores with other parts to If the system is porous, fill the pores with other parts to deliver different functions or to achieve the desired deliver different functions or to achieve the desired results.results.
o
oImpart certain spatial structure to your system (e.g. Impart certain spatial structure to your system (e.g. networks).networks).
o
oIntroduce “filtering membranes” to diminish the influence Introduce “filtering membranes” to diminish the influence of harmful factors of the environment or other system’s of harmful factors of the environment or other system’s parts.parts.
Examples
Examples((ITIT))

BuiltBuilt--ininbuffersbuffers::diskdiskbuffers,buffers,filefilebuffers,buffers,aakeyboardkeyboardbuffer,buffer,datadatabuffers,buffers,andandotherother

IntroductionIntroductionofofregularregularpausespausesduringduringexecutionexecutionofofoperationsoperations

IntegrationIntegrationofofsomesomeentertainingentertainingfeaturesfeaturesintointoananapplicationapplicationtotopreventpreventaalonglongprocessprocess(for(forexample,example,installationinstallationororstartstartofofananapplication)application)beingbeinginterruptedinterruptedbybyaauseruser
34
34
CONFIDENTIAL
CONFIDENTIAL
#32
#32::COLOR CHANGECOLOR CHANGE
Examples
Examples((Business SystemsBusiness Systems))

“Transparent”“Transparent”organizationsorganizations

ShipmentShipmenttrackingtrackingfunctionsfunctions

“Transparent”“Transparent”stepsstepsofofaaprocessprocessororthethestepsstepsthatthatcancanbebeskippedskippedunderundersomesomeconditionsconditions

UseUseofofdifferentdifferentcolorscolorsininairportsairportstotomarkmarkdifferentdifferentclassesclassesorordifferentdifferentcustomscustomscontrolcontrolzoneszones

UseUseofofdifferentdifferentcolorscolorstotoevokeevokedifferentdifferentassociationsassociationsamongamongcustomerscustomers
Strategies
Strategiesand Recommendationsand Recommendations
o
oChange the visibility degree of different parts of your Change the visibility degree of different parts of your system respectively to other system parts or the system respectively to other system parts or the supersystemsupersystem
o
oChange color of an object/system, its part, or environmentChange color of an object/system, its part, or environment
o
oUse different colors to highlight different parts or different Use different colors to highlight different parts or different functionsfunctions
o
oChange transparency of a system/ object, its part or Change transparency of a system/ object, its part or environmentenvironment
o
oMake your process or its part as transparent as possibleMake your process or its part as transparent as possible
o
oHighlight the distinguishing property of your Highlight the distinguishing property of your object/system/processobject/system/process
Examples
Examples((ITIT))

SemiSemi--transparenttransparentbuttonsbuttonsininsoftwaresoftwaresystemssystemstotomarkmarkinaccessibleinaccessiblecommandscommands

UseUseofofdifferentdifferentcolorscolorsininaawebweb--basedbasedsystemsystemtotodrawdrawusers’users’attentionattentiontotoanyanychangedchangedconditionsconditions

UseUseofofcolorscolorstotodrawdrawusers’users’attentionattentiontotosomesomespecialspecialsituationssituations(for(forexample,example,coloredcoloredunderliningunderliningofofthethewordswordsthatthathavehavespellingspellingmistakes)mistakes)

DataDataexport/importexport/importfromfromoneoneformatformatintointoanotheranother

ChangeChangeofofdatadatatypetype(float(floattotointeger,integer,datatimedatatimetotosmalldatatimesmalldatatime,,numericnumerictotofinancial)financial)
35
35
CONFIDENTIAL
CONFIDENTIAL
#33
#33::HOMOGENITYHOMOGENITY
Examples
Examples((Business SystemsBusiness Systems))

AllAllprojectprojectteamsteamsininoneonelocationlocation

ProductProductlineslines

WorkingWorkingTogetherTogetherTeamTeamprogramprogrambybyBoeingBoeing——supplierssuppliersandandconsumersconsumersareareunitedunitedwithinwithinaasinglesingleprojectprojectcyclecycle

TeachTeachsupplierssuppliersyouryourprinciplesprinciplesofofwork,work,gettinggettingthemthembetterbetterunderstandunderstandyouryourbusinessbusiness

IncludeIncludethethebestbestusersusersininthetheteamsteamsthatthatdevelopdevelopnewnewproductsproductsororservicesservices
Strategies
Strategiesand Recommendationsand Recommendations
o
oImpair the interacting objects or parts of the system the Impair the interacting objects or parts of the system the same structure with similar or identical properties.same structure with similar or identical properties.
o
oCompose your system from a number of homogeneous Compose your system from a number of homogeneous objects.objects.
o
oMake some parts of your system homogeneous with your Make some parts of your system homogeneous with your supersystemsupersystem..
o
oMake some parts of your process, which interact with Make some parts of your process, which interact with supersystemsupersystem, homogeneous with the , homogeneous with the supersystemsupersystem..
Examples
Examples((ITIT))

DevelopingDevelopingaanewnewapplicationapplicationcompatiblecompatiblewithwithearlierearlierversions,versions,enablingenablingthethenewernewerversionversiontotosupportsupportthethedatadataandandfilesfilescreatedcreatedininthosethoseearlierearlierversionsversions

UsingUsingananelementaryelementarydatadataformatformatforforeditingediting

DataDatacontainers,containers,suchsuchasasarrays,arrays,containcontainthetheelementselementsofofsimilarsimilartypestypes
36
36
CONFIDENTIAL
CONFIDENTIAL
#3
#34:4:DISCARD AND RECOVERDISCARD AND RECOVER
Examples
Examples((Business SystemsBusiness Systems))

InvitingInvitingexternalexternalconsultantsconsultants

TheThetaskstasksthatthatappearappearandanddisappeardisappeardynamicallydynamicallywithinwithinaabusinessbusinessprocessprocess

InvolvingInvolvingthetheretiredretiredemployeesemployeesforforworkingworkingduringduringthethepeakpeakloadloadperiodsperiods

ProvisionProvisionofofthetheconfiguredconfiguredservicesserviceswherewheresomesomeelementselementscancanbebeaddedaddedororremovedremoved
Strategies
Strategiesand Recommendationsand Recommendations
o
oIf your system has to include some partIf your system has to include some partthat only operates that only operates at a certain moment ofat a certain moment oftime, consider introducing this part time, consider introducing this part onlyonlywhen necessary and then remove it.when necessary and then remove it.
o
oConsider if an activity is needed each timeConsider if an activity is needed each timewhen a process when a process runs. If not, make thisruns. If not, make thisactivity be included into the process activity be included into the process only whenonly whenneeded.needed.
o
oIf some part of the system has fulfilled itsIf some part of the system has fulfilled itsfunction and function and becomes unnecessary orbecomes unnecessary orproduces negative effect, produces negative effect, eliminate or modifyeliminate or modifyit so that it will not produce any it so that it will not produce any negative effect.negative effect.
o
oAdd the components to your system that willAdd the components to your system that willautomatically automatically eliminate those parts of youreliminate those parts of yoursystem which have become system which have become unnecessary.unnecessary.
o
oRestore the consumable parts of the systemRestore the consumable parts of the systemduring during operation.operation.
Examples
Examples((ITIT))

TheThegarbagegarbagecollectioncollectionmechanismmechanismininJavaJavaoror..NETNETregularlyregularlycleanscleansupupunnecessaryunnecessaryobjectsobjectsfromfrommemorymemory

AutomaticAutomaticunloadingunloadingfromfrommemorymemorythetheCOMCOMcomponentscomponentsthatthatarearenotnotusedusedbybyanyanyapplicationsapplications

TheThebacktrackingbacktrackingmechanismmechanisminindatabasesdatabaseshelpshelpsrestorerestorethethetransactionstransactionsthatthathavehavebeenbeendonedonebeforebefore
37
37
CONFIDENTIAL
CONFIDENTIAL
#3
#35:5:PARAMETER CHANGEPARAMETER CHANGE
Examples
Examples((Business SystemsBusiness Systems))

IncreaseIncreaseorordecreasedecreasethethesizesizeofofyouryourprojectprojectteamteamdependingdependingononthetheprojectprojectstagestageandandconditionsconditions

“Warm“Warmup”up”thethemarketmarketbeforebeforeaanewnewproductproductreleaserelease

ChangeChangethetheenvironmentenvironmentforforbrainstormingbrainstormingsessionssessions

ThereThereisisaapracticepracticeofofusingusingairairpumpspumpsininsupermarketssupermarketstotospreadspreadaroundaroundthethesmellsmellofoffreshfreshbakedbakedbreadbread
Strategies
Strategiesand Recommendationsand Recommendations
o
oVary parameters of your systemVary parameters of your systemadaptively.adaptively.
o
oInstead of developing a new expensiveInstead of developing a new expensivesystem or a process, system or a process, find afind aresource that is already available and can serve asresource that is already available and can serve aspartially developed object/process.partially developed object/process.
o
oChange the degree of flexibility of aChange the degree of flexibility of asystem.system.
o
oChange your system’s or object’sChange your system’s or object’sphysical state.physical state.
o
oInstead of expensive solid objects, useInstead of expensive solid objects, usevirtual copies, virtual copies, models, cheap objects, andmodels, cheap objects, andvice versa.vice versa.
o
oChange concentration or consistency of aChange concentration or consistency of asystem/object.system/object.
o
oChange emotional parameters.Change emotional parameters.
o
oChange visual parameters.Change visual parameters.
o
oChange other sensory parameters.Change other sensory parameters.
Examples
Examples((ITIT))

ChangingChangingthetheworkingworkinglanguagelanguageininappsapps

ChangingChangingthethescreenscreenresolutionresolution

VirtualVirtualprototypingprototyping

UsingUsingthetheexistingexistingSkypeSkypeplatformplatformforforthethedevelopmentdevelopmentofofIPIPtelephonytelephonyproductsproducts
38
38
CONFIDENTIAL
CONFIDENTIAL
#3
#36:6:PARADIGM SHIFTPARADIGM SHIFT
Examples
Examples((Business SystemsBusiness Systems))

ChangeChangethetheparadigmparadigmtotomakemakeorganizationalorganizationalchangeschangesintegratedintegrated

ConsultingConsultingcompaniescompaniesadaptadapttheirtheiroffersoffersdependingdependingononthethemarketmarketsituationsituation..TheyTheyofferofferthetheservicesservicesononbusinessbusinessshrinkageshrinkageduringduringcrisescrisesandandthetheservicesservicesononbusinessbusinessexpansionexpansionduringduringmarketmarketboomsbooms..

FormingForming\\StormingStorming\\NormingNorming\\PerformingPerforming——thethestagesstagesofofteamteamformationformationwherewhereaadropdropofofenthusiasmenthusiasmisiscompensatedcompensatedduringduringthethestormingstorming--normingnormingstagesstages
Strategies
Strategiesand Recommendationsand Recommendations
o
oUse the phenomena occurring at macroscaleUse the phenomena occurring at macroscaleto shift the to shift the paradigms within yourparadigms within yoursystem.system.
o
oUse the external “push” factors to achieveUse the external “push” factors to achievethe necessary the necessary changes in your system orchanges in your system orprocess.process.
o
oCreate the internal “push” factors toCreate the internal “push” factors toachieve necessary achieve necessary changes in yourchanges in yoursystem or process.system or process.
Examples
Examples((ITIT))

TheThetransitionstransitionslikelikeJavaJavacodecode-->>bytecodebytecode-->>nativenativemachinemachinecodecode

AnalogAnalog--toto--digitaldigitalconversionconversion

UseUseofofquantumquantumeffectseffects
39
39
CONFIDENTIAL
CONFIDENTIAL
#3
#37:7:RELATIVE CHANGERELATIVE CHANGE
Examples
Examples((Business SystemsBusiness Systems))

UseUseexpansionexpansionororcontractioncontractionofofthethemarketingmarketingeffortseffortsdependingdependingononthetheproductproductratingsratingsororsalessalesvolumevolume

CombiningCombininghighhigh--riskriskandandhighhigh--reliabilityreliabilityinvestmentinvestmentstrategiesstrategiesatatturbulentturbulentmarketsmarkets

BringBringtogethertogetheremployeesemployeeswithwithdifferentdifferentskillsskillsandandcompetenciescompetenciestotoformformcrosscross--functionalfunctionalteamsteams
Strategies
Strategiesand Recommendationsand Recommendations
o
oConsider using the already existingConsider using the already existingdifferences between differences between differentdifferentcomponents of your system to achievecomponents of your system to achievepositive positive effects.effects.
o
oUse the dynamic “expansionUse the dynamic “expansion--contraction”contraction”effects.effects.
o
oMerge two components of your systemMerge two components of your systemwith similar with similar parameters to achieveparameters to achievesynergy.synergy.
o
oUse ongoing changes in the Use ongoing changes in the supersystemsupersystemto achieve positive to achieve positive effects or modifyeffects or modifyyour system/process.your system/process.
Examples
Examples((ITIT))

ComputerComputermemorymemoryisisaacombinationcombinationofofactiveactivememorymemory(in(inCPU)CPU)andandindividualindividualmemorymemoryframesframes(such(suchasascachecacheandandvirtualvirtualmemory)memory)..ExpansionExpansionandandcontractioncontractionofofthisthisresourceresourcehelpshelpsachieveachievethethemaximummaximumperformanceperformanceraterateofofthethecomputercomputeratatthethegivengiventimetime..

DeltaDeltaAAnalysisnalysis——aacomparisoncomparisonofoftwotwoentitiesentitiesbybymeasuringmeasuringthethedegreedegreeofoftheirtheirchangechange..
40
40
CONFIDENTIAL
CONFIDENTIAL
#3
#38:8:ENRICHED ENVIRONMENTENRICHED ENVIRONMENT
Examples
Examples((Business SystemsBusiness Systems))

UseUseofofappliedappliedgamesgamesininthethetrainingtrainingprocessprocess

InvolvingInvolvingindependentindependentexpertsexpertsininaasalesalenegotiatingnegotiating

FocusingFocusingthetheproductproductmarketingmarketingeffortseffortsononthethemarketmarketsegmentssegmentswherewherethethecustomerscustomerswhowhoareareawareawareofofsimilarsimilarproductsproductsarearealreadyalreadypresentpresent

OpenOpen--typetypekitchenskitchensininrestaurantsrestaurants

ProductProductdemonstrationsdemonstrationsininthetherealrealoperationoperationconditionsconditions
Strategies
Strategiesand Recommendationsand Recommendations
o
oConduct required processes orConduct required processes oractivities within the activities within the “enriched”“enriched”environments.environments.
o
oCreate an “enriched” environment forCreate an “enriched” environment foryour system by your system by bringing suchbringing suchcomponent(s) to the environment thatcomponent(s) to the environment thatwill will boost your system’s performanceboost your system’s performanceor help achieve the or help achieve the desired effects.desired effects.
o
oModify the existing components of yourModify the existing components of yoursystem’s system’s environment in a such a wayenvironment in a such a waythat this will boost your that this will boost your system’ssystem’sperformance or help achieve theperformance or help achieve thedesired effects.desired effects.
Examples
Examples((ITIT))

UpdatingUpdatingananapplicationapplicationtotoaanewernewerversionversion

CreatingCreatingwebweb--enabledenabledapplicationsapplications

IncludingIncludingaa“how“how--toto--use”use”videovideotutorialtutorialininHelpHelp
41
41
CONFIDENTIAL
CONFIDENTIAL
#3
#39:9:INERT ENVIRONMENTINERT ENVIRONMENT
Examples
Examples((Business SystemsBusiness Systems))

InvolvingInvolvingananindependentindependent(neutral)(neutral)thirdthirdpartypartyininholdingholdingdifficultdifficultnegotiationsnegotiations

SoundproofSoundproofdesigndesignofofsomesomesectionssectionsininaastorestore(for(forexample,example,artartgalleries)galleries)

AfterAfterthetheWorldWorldWarWarIIIIthetheUnitedUnitedStatesStatestriedtriedtotomakemakeuseuseofofGermanGermanchemistrychemistrypatentspatents..ToTotheirtheirsurprise,surprise,thetheresultsresultsofofmanymanychemicalchemicalreactionsreactionswereweredifferentdifferentfromfromtheirtheirdescriptiondescriptionininthethepatentspatents..LaterLaterititbecamebecameknownknownthatthatsomesomeimportantimportantinformationinformationononthosethosereactionsreactionshadhadbeenbeenremovedremovedfromfromthethepatentpatentdescriptionsdescriptions..
Strategies
Strategiesand Recommendationsand Recommendations
o
oReplace the existing environment with anReplace the existing environment with aninert one.inert one.
o
oPlace your system into a “vacuumed”Place your system into a “vacuumed”environment.environment.
o
oIsolate your system or process from itsIsolate your system or process from itsenvironment.environment.
o
oIf possible, remove the componentsIf possible, remove the componentsfrom your system’s from your system’s environment thatenvironment thatproduce negative effects on your system produce negative effects on your system performance.performance.
o
oAdd neutral parts to anAdd neutral parts to anobject/system.object/system.
Examples
Examples((ITIT))

DataDataCalmingCalming——aadatadataprocessingprocessingthatthatdeletesdeletes“spikes”“spikes”fromfromdatadatasamplessamples

UsingUsingbufferbufferzoneszones
42
42
CONFIDENTIAL
CONFIDENTIAL
#
#40:40:COMPOSITE STRUCTURESCOMPOSITE STRUCTURES
Examples
Examples((Business SystemsBusiness Systems))

MultiMulti--disciplinedisciplineprojectprojectteamsteams

ConductConducttrainingstrainingsbybycombiningcombininglectures,lectures,practicepracticesessions,sessions,appliedappliedgames,games,videos,videos,etcetc..

ComposeComposethethenegotiationnegotiationteamsteamsininaawaywaytheytheyincludeincludebothbothhardlinershardlinersandandflexibleflexiblenegotiatorsnegotiators

MultiMulti--culturalculturalcreativecreativeteamsteams

InvolvingInvolvingusersusersininthetheteamsteamsthatthatdevelopdevelopnewnewproductsproducts

ResearchResearchandandMarketingMarketingDepartmentDepartment
Strategies
Strategiesand Recommendationsand Recommendations
o
oCreate composite systems, consistingCreate composite systems, consistingof smaller systems or of smaller systems or objects withobjects withdifferent or “biased” parametersdifferent or “biased” parametersinstead of instead of uniform ones.uniform ones.
o
oCreate composite systems fromCreate composite systems fromsystems or objects with systems or objects with oppositeoppositeproperties.properties.
o
oCreate compositions in the form of layersCreate compositions in the form of layerswith different with different properties.properties.
o
oLink two different processes orLink two different processes oractivities.activities.
o
oCreate combinations of differentCreate combinations of differentfunctions, skills, and functions, skills, and capabilities.capabilities.
Examples
Examples((ITIT))

UsingUsingcompositecompositekeyskeysinindatabasesdatabases..((AAcompositecompositekeykeyconsistsconsistsofoftwotwoorormoremoreprimaryprimarykeyskeys..))

UseUseofofcomplexcomplexindexesindexes..

UsingUsingrolesrolesinsteadinsteadofofspecificspecificusersuserstotoconfigureconfigurepermissionspermissions

ExecutingExecutingaaseparateseparateprocessprocessininaaseparateseparatememorymemorysegmentsegmentmakesmakesititpossiblepossibletotorunrunseveralseveralapplicationsapplicationsononaasinglesinglecomputercomputer