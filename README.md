# EDMM10-Modbus-Home-Assistant
A modbus configuration for SMA EDMM10 for Home assistant

A state of '-2147483648' in home assistant seems to mean that the unit is not outputting any value. This means that when there is no power produced the state  of i.e "sma_edmm_current_pv_feed_in_active_power_on_all_line_conducors" will be '-2147483648' and has to be accounted for in home assistant. I did this using node red. See example in repo.
