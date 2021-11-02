# Grand Theft Auto V Fast Train and Tram
This is a mod for GTA V to make the train and the tram faster.

You can even configure the speed of the train if you want it even faster!

## How to Install
Place the traintracks.xml file to update\update.rpf\common\data\levels\gta5\

## Informations
The train track that have a filename "trains1.dat" is the train/freight track.

The train track that have a filename "trains4.dat" is the tram/subway/metro track.

The speed value in meters per second determines how fast is the train.

The brakingDist determine how far the train will brake from the train station in meters.

### The value of the braking distance (brakingDist)
Based on our experiment, the value of the brakingDist of the freight track should be the speed multipiled by 4.

brakingDist = 4x where x is the speed of the freight train in m/s.

Ex. If speed is 40, brakingDist should be 160.

While the value of the brakingDist of the metro track should be the speed multipiled by 3.

brakingDist = 3x where x is the speed of the metro train in m/s.

Ex. If speed is 35, brakingDist should be 105.

If the brakingDist is lower than the suggested value, the train will not stop or overshoot at the train station.

If the brakingDist is higher than the suggested value, the train will stop before reaching the train station.

## Demo
https://www.youtube.com/watch?v=pm-fRtqKjjQ