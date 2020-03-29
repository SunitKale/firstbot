## happy path
* greet
  - utter_greet

## sad path 2
* greet
  - utter_greet

## sad path 1
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## general information
* general{"name":"principle","name":"principal"}
  - utter_priname

## clg information
* clg_info{"services":"facilities"}
  - utter_facilities

## clg information 1
* clg_info{"info":"contact"}
  - utter_contact

## clg information 2
* clg_info{"services":"bus facility","services":"bus service","services":"bus"}
  - utter_bus
  - utter_routes

## clg information 3
* clg_info{"info":"routes","services":"bus","info":"address","info":"location"}
  - utter_routes

## clg information 4
* clg_info{"services":"wifi"}
  - utter_wifi

## clg information 5
* clg_info{"services":"hostel facilities"}
  - utter_HostelFac
  - utter_hostel

## clg information 6
* clg_info{"services":"parking"}
  - utter_parking

## clg information 7
* clg_info{"services":"parking charges"}
  - utter_ParkCharge

## clg information 8
* clg_info{"services":"departmental library"}
  - utter_DeptLibrary

## clg information 9
* clg_info{"services":"canteen"}
  - utter_CanteenFac

## centra lib
* cnt_lib{"info":"books","services":"Library"}
  - utter_bkquantity
  - utter_jrquantity
  - utter_magquantity
  - utter_compbkquantity
  - utter_mechbkquantity

## central lib c
* cnt_lib{"info":"journals","services":"Library"}
  - utter_jrquantity

## central lib java
* cnt_lib{"info":"magazines","services":"Library"}
  - utter_magquantity

## central lib esiot 
* cnt_lib{"info":"comp dept","services":"Library","info":"computer dept","info":"computer department","info":"computer"}
  - utter_compbkquantity

## central lib esrtos
* cnt_lib{"info":"mech dept","services":"Library","info":"mechanical dept","info":"mechanical department","info":"mechanical"}
  - utter_mechbkquantity

## central lib isee
* cnt_lib{"info":"collection","services":"Library"}
  - utter_bkquantity
  - utter_jrquantity
  - utter_magquantity
  - utter_compbkquantity
  - utter_mechbkquantity

## admin
* admin{"admin_proc":"Admission","proc":"process","admin proc":"FE Admission"}
  - utter_feadmission
  - utter_admindoc

## ebc
* admin{"info":"contact","name":"reception","name":"college"}
  - utter_clgcontact

## earn and learn
* admin{"admin_proc":"SE Admission","proc":"process","admin_proc":"SY Admission","admin_proc":"direct SE Admission"}
  - utter_seadmission

## account
* admin{"info":"fee","info":"fees","name":"college"}
  - utter_fee

## cashier
* admin{"info":"coordinator","name":"EBC Scholarship section"}
  - utter_EBCname

## scholarship
* admin{"name":"EBC Scholarship section"}
  - utter_EBCname
  - utter_EBCdoc

## admision
* admin{"info":"documents","scholar":"EBC"}
  - utter_EBCdoc

## seat arrangement 1
* admin{"quantity":"intake","info":"computer"}
  - utter_compseats

## seat arrangement 2
* admin{"quantity":"seats","info":"computer"}
  - utter_compseats

## seat arrangement 3
* admin{"quantity":"intake","info":"mechanical"}
  - utter_mechseats

## seat arrangement 4
* admin{"quantity":"seats","info":"mechanical"}
  - utter_mechseats

## doc
* admin{"info":"documents","admin_proc":"admission"}
  - utter_admindoc

## comp dept
* comp_dept{"name":"who is topper","div":"BE"}
  - utter_BEtop

## compse 1
* comp_dept{"name":"CR","div":"SE1"}
  - utter_SE1cr

## compse 2
* comp_dept{"name":"CR","div":"SE2"}
  - utter_SE2cr

## compbe 1
* comp_dept{"name":"CR","div":"BE1"}
  - utter_BE1cr

## compbe 2
* comp_dept{"name":"CR","div":"BE2"}
  - utter_BE2cr

## comp teacher se1
* comp_dept{"name":"Class teacher","div":"SE1"}
  - utter_clsSE1

## comp teacher se2
* comp_dept{"name":"Class teacher","div":"SE2"}
  - utter_clsSE2

## comp teacher te1
* comp_dept{"name":"Class teacher","div":"TE1"}
  - utter_clsTE1

## comp teacher te2
* comp_dept{"name":"Class teacher","div":"TE2"}
  - utter_clsTE2

## comp teacher be1
* comp_dept{"name":"Class teacher","div":"BE1"}
  - utter_clsBE1

## comp teacher be2
* comp_dept{"name":"Class teacher","div":"BE2"}
  - utter_clsBE2

## comp faculty total
* comp_dept{"quantity":"total","info":"faculty"}
  - utter_FacCount

## comp faculty count
* comp_dept{"quantity":"count","info":"faculty"}
  - utter_FacCount

## comp faculty coordinator
* comp_dept{"name":"Coordinater","group":"CSI"}
  - utter_CSIhead

## Placement
* placement{"pack":"Highest Package","dept":"computer"}
  - utter_HighPack

## placement salary
* placement{"pack":"Highest Salary","dept":"computer"}
  - utter_HighPack

## placement package
* placement{"pack":"Highest Package","info":"college"}
  - utter_HighPack

## placement companies
* placement{"name":"Top companies","dept":"computer"}
  - utter_TopCompy

## placement recruiters
* placement{"name":"Top recruiters","dept":"computer"}
  - utter_TopCompy

## placement head
* placement{"name":"Head of placement"}
  - utter_HeadPlace

## placement coorhead
* placement{"name":"coordinator"}
  - utter_StudCooPlace

## Developer info
* deve{"team":"developers"} 
  - utter_dev

## interactive_story_1
* general{"name": "priciple"}
    - utter_priname

## interactive_story_2
* admin{"name": "college"}

## registrar
* registrar{"name":"who is the registrar","name":"what is the name of registrar"}
    - utter_registrar

## New Story 1
* comp_dept
    - utter_BE1cr

## New Story 2
* comp_dept
    - utter_fecr

## New Story 3
* greet
    - utter_greet

## New story 4
* greet
    - utter_greet

## New story 5
* admin
    - utter_feadmission
    - utter_admindoc

## New virus
* comp_dept
    - utter_sinu

## New Story 6
* greet
    - utter_greet

## New story default
* admin
    - action_default_fallback

## New Story 7
* general{"name":"principle"}
    - utter_priname

## New story 8
* general{"name":"principle"}
    - utter_priname

## New Story 9

* comp_dept{"name":"topper"}
    - utter_BEtop

## New story 10
* comp_dept{"name":"topper"}
    - utter_BEtop

## New Story 11
* comp_dept{"name":"topper"}
    - utter_BEtop

## New Story 12
* general{"name":"principle"}
    - utter_priname

## New story 13
* comp_dept{"name":"topper"}
    - utter_BEtop

## mathematics 1
* general{"name":"HOD of computer departement"}
    - utter_hodname

## mathematics 2
* greet
    - utter_greet

## discrete mathematics 
* general{"name": "principle"}
    - utter_priname

## basic of civil
* comp_dept{"name": "CR", "div": "BE"}
    - utter_BE1cr

## chemistry
* comp_dept{"name": "topper", "div": "BE"}
    - utter_BEtop

## physics
* admin{"admin_proc": "admission", "proc": "process"}
    - utter_feadmission

## basic of electrical
* admin{"info": "computer", "admin_proc": "admission", "proc": "process"}
    - utter_seadmission

## basic of electronic
* clg_info{"services": "canteen"}
    - utter_CanteenFac
    - utter_contact

## graphics
* goodbye
    - utter_goodbye

## fpl 1
* general{"name":"principle"}
    - utter_priname

## fpl 2
* comp_dept{"name":"CR","div":"BE"}
    - utter_BE1cr

## basic of mechanical
* clg_info{"services":"canteen"}
    - utter_facilities

## data structure
* admin{"name":"college"}
    - utter_contact

## advance data structure
* admin{"name":"college"}
    - action_default_fallback

## object oriented
* admin{"admin_proc":"admission","proc":"process"}
    - utter_feadmission

## New Story

* placement{"name":"head"}
    - utter_HeadPlace

## interactive_story_1
* general{"name": "college"}
    - utter_priname
* general{"name": "principle"}
    - utter_priname
* general{"name": "principle"}
    - utter_priname

## interactive_story_1
* general{"name": "principle"}
    - utter_priname
* general{"name": "HOD"}
    - utter_hodname
* admin
    - utter_CanteenFac
* placement{"name": "Head"}
    - utter_HeadPlace
* clg_info
    - utter_facilities
* admin{"info": "contact", "name": "college"}
    - utter_clgcontact
* clg_info{"services": "bus"}
    - utter_bus
    - utter_routes
* clg_info{"services": "hostel facilities", "name": "college"}
    - utter_HostelFac
* cnt_lib{"services": "library"}
    - utter_bkquantity
    - utter_jrquantity
    - utter_magquantity
    - utter_compbkquantity

## interactive_story_1
* admin{"admin_proc": "admission", "proc": "process"}
    - utter_feadmission
* admin{"admin_proc": "admission", "proc": "process"}
    - utter_seadmission
* admin{"info": "contact", "name": "college"}
    - utter_contact
* admin{"info": "coordinator", "name": "EBC section"}
    - utter_EBCname
* admin{"quantity": "intake"}
    - utter_compseats
* admin{"quantity": "seats", "info": "mechanical"}
    - utter_mechseats
* comp_dept{"name": "topper", "div": "BE"}
    - utter_BEtop
* comp_dept{"name": "CR", "div": "SE1"}
    - utter_SE1cr
* comp_dept{"name": "CR", "div": "SE2"}
    - utter_SE2cr
* comp_dept{"name": "CR", "div": "BE1"}
    - utter_BE1cr
* comp_dept{"name": "CR", "div": "BE2"}
    - utter_BE2cr

## interactive_story_1
* comp_dept{"name": "class teacher", "div": "SE1"}
    - utter_clsSE1
* comp_dept{"name": "Class teacher", "div": "SE2"}
    - utter_clsSE2
* comp_dept{"name": "Class teacher", "div": "TE1"}
    - utter_clsTE1
* comp_dept{"name": "Class teacher", "div": "TE2"}
    - utter_clsTE2
* comp_dept{"name": "Class teacher", "div": "BE1"}
    - utter_clsBE1
* comp_dept{"name": "Class teacher", "div": "BE2"}
    - utter_clsBE2
* comp_dept{"quantity": "total", "info": "faculty"}
    - utter_FacCount
* comp_dept{"quantity": "total", "info": "faculty"}
    - utter_FacCount
* comp_dept{"info": "coordinator", "group": "CSI"}
    - utter_CSIhead
* placement{"pack": "highest package", "dept": "computer"}
    - utter_HighPack

## interactive_story_1
* general{"name": "HOD", "info": "computer"}
    - utter_priname
* placement{"info": "coordinator"}
    - utter_StudCooPlace
* placement{"pack": "highest"}
    - utter_HighPack
* placement{"name": "top companies", "dept": "computer"}
    - utter_TopCompy

## interactive_story_1
* placement{"name": "top companies", "dept": "computer"}
    - utter_TopCompy
