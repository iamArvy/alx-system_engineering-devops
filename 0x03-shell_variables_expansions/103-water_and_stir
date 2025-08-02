#!/bin/bash

echo "ibase=$water; WATER=$WATER" | bc > tmp1
echo "ibase=$stir; STIR=$STIR" | bc > tmp2

sum=$(echo "$(cat tmp1) + $(cat tmp2)" | bc)
echo "obase=$bestchol; $sum" | bc
