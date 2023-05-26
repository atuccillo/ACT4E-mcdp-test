# PrimitiveDPs

These objects corresponds to morphisms in the category of design problems DP.


## Common DP interface

::: act4e_mcdp.primitivedps
    options:
      members:
        - PrimitiveDP


## Conversions

::: act4e_mcdp.primitivedps
    options:
      members:
        - AmbientConversion
        - UnitConversion  


## Plumbing

::: act4e_mcdp.primitivedps
    options:
      members:
        - JoinNDP
        - MeetNDualDP  


## Simple unary mathematical operations


::: act4e_mcdp.primitivedps
    options:
      members:
        - M_Ceil_DP
        - M_FloorFun_DP  
 

## Adding or multiplying by a constant


::: act4e_mcdp.primitivedps
    options:
      members:
        - ValueFromPoset
 


::: act4e_mcdp.primitivedps
    options:
      members:
        - M_Fun_AddConstant_DP
        - M_Res_AddConstant_DP
        - M_Fun_MultiplyConstant_DP
        - M_Res_MultiplyConstant_DP




## Adding or multiplying functionality and resources together


::: act4e_mcdp.primitivedps
    options:
      members:
        - M_Fun_AddMany_DP
        - M_Res_AddMany_DP
        - M_Fun_MultiplyMany_DP
        - M_Res_MultiplyMany_DP

    

## Composite DPs

::: act4e_mcdp.primitivedps
    options:
      members:
        - DPSeries