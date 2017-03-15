# Info2Action
STATA code for Information to Action article
#Samoa

#Table 1
firthlogit mediumdummy ib(1).region_num i.employmentstatus age i.sex  i.smartphone i.trustgovforemergencyrelief i.trustmataiorganizerelief
firthlogit sourcedummy ib(1).region_num i.employmentstatus age i.sex  i.smartphone i.trustgovforemergencyrelief i.trustmataiorganizerelief

#Table 3
firthlogit whatsourcesact_mobsms ib(1).region_num i.employmentstatus age i.sex  i.smartphone i.trustgovforemergencyrelief i.trustmataiorganizerelief
firthlogit whatsourcesact_internet ib(1).region_num i.employmentstatus age i.sex  i.smartphone i.trustgovforemergencyrelief i.trustmataiorganizerelief
firthlogit whatsourcesact_newspaper ib(1).region_num i.employmentstatus age i.sex i.smartphone i.trustgovforemergencyrelief i.trustmataiorganizerelief
firthlogit whatsourcesact_radio ib(1).region_num i.employmentstatus age i.sex i.smartphone i.trustgovforemergencyrelief i.trustmataiorganizerelief
firthlogit whatsourcesact_tv ib(1).region_num i.employmentstatus age i.sex i.smartphone i.trustgovforemergencyrelief i.trustmataiorganizerelief

#Table 5
firthlogit sourcedummy ib(1).region_num i.employmentstatus age i.sex i.trustgovforemergencyrelief i.trustmataiorganizerelief facebook twitter 
firthlogit sourcedummy ib(1).region_num i.employmentstatus age i.sex  i.smartphone i.trustgovforemergencyrelief i.trustmataiorganizerelief  
firthlogit sourcedummy ib(1).region_num i.employmentstatus age i.sex  i.smartphone i.trustgovforemergencyrelief i.trustmataiorganizerelief facebook twitter 

#Table 6
firthlogit whatsourcesact_mobsms ib(1).region_num i.employmentstatus age i.sex i.trustgovforemergencyrelief i.trustmataiorganizerelief facebook twitter 
firthlogit whatsourcesact_mobsms ib(1).region_num i.employmentstatus age i.sex  i.smartphone i.trustgovforemergencyrelief i.trustmataiorganizerelief  
firthlogit whatsourcesact_mobsms ib(1).region_num i.employmentstatus age i.sex  i.smartphone i.trustgovforemergencyrelief i.trustmataiorganizerelief facebook twitter 

#Kenya

#Table 2
firthlogit medium_dummy age gender smartphone householdexpenses turstgovsec localleadersec
firthlogit source_dummy age gender smartphone householdexpenses turstgovsec localleadersec
firthlogit sourceactmobile age gender smartphone householdexpenses turstgovsec localleadersec

#Table 4
firthlogit sourceactinternet age gender smartphone householdexpenses turstgovsec localleadersec
firthlogit sourceactnewspaper age gender smartphone householdexpenses turstgovsec localleadersec
firthlogit sourceactradio age gender smartphone householdexpenses turstgovsec localleadersec
firthlogit sourceacttv age gender smartphone householdexpenses turstgovsec localleadersec
