"# visualstudio-xamarin--android" 

A few days ago, there was a new requirement. Customers use vs development tools to develop based on xamarin.
Therefore, try to develop Android apps based on vs2019 and xamarin.A problem occurred when relying on the 
java jar package,vs compilation always reports that no relevant java class can be found.After investigation, 
it was found that replacing the SDK that xamarin depends on solved the problem.
