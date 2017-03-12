# Bike_sharing_dataset

Based on the popular UCI ML repositories Bike Sharing Dataset, competition hosted by kaggle

**Data Fields**                                                                            
*datetime* - hourly date + timestamp                                                                                      
*season* -  1 = spring, 2 = summer, 3 = fall, 4 = winter                                                         
*holiday* - whether the day is considered a holiday                                                              
*workingday* - whether the day is neither a weekend nor holiday                                                 
*weather* - 1: Clear, Few clouds, Partly cloudy, Partly cloudy                                                                       
            2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist                                                        
            3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds                                
            4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog                                                       
*temp* - Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)                                                                                             
*atemp* - Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in                                                                                                                                 hourly scale)
*humidity* - Normalized humidity. The values are divided to 100 (max)                                                                   
*windspeed* - Normalized wind speed. The values are divided to 67 (max)                                              
*casual* - count of casual users                                                                                   
*registered* - count of registered users                                                                             
*count* - count of total rental bikes including both casual and registered
