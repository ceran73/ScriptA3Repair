_timeForRepair = 150; 
 
_vehicle = vehicle player; 
 
hint format ["Please wait %1 seconds for repair",_timeForRepair]; 
 
if (_vehicle == player) then 
 
{_vehicle = cursorTarget;}; 
  
_vehicle setdamage 0; 
 
_vehicle = nil; 
 
_vehicle = _this select 0; 

_vehicle setVariable ["stopcooldown",FALSE];

sleep _timeForRepair; 

_vehicle setVariable ["stopcooldown",TRUE];
