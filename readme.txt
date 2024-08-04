See Wiki https://github.com/peno64/slimmemeter/wiki

Note that the wiki page "electricity peak current month" is not valid when using this YAML. The 2023.7 update of ESPHome officially added support for peak values. This YAML simply utilizes these readouts to show 3 peak values:
     
    active_energy_import_current_average_demand:
      name: "Peak Current Average Quarterly Demand"
      icon: mdi:chart-sankey
    active_energy_import_maximum_demand_running_month:
      name: "Peak Month Maximum Quarterly Demand"
      icon: mdi:chart-sankey
    active_energy_import_maximum_demand_last_13_months:
      name: "Peak 13 Month Maximum Quarterly Demand"
      icon: mdi:chart-sankey

All other pages remain valid.
