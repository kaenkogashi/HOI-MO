Explanation of HOI-MO (Human-Object Interaction with Missing Objects) test sets' CSV headers

The total samples of V-COCO-MO are 2376. V-COCO-MO is write in the HOI_MO_COCO2376.csv file.
The total samples of HICO-DET-MO are 3572. HICO-DET-MO is write in the HOI_MO_HICO3572.csv file.

Image_ID: image id of V-COCO or HICO-DET
x1,	y1,	x2	,y2: HOI_MO's human bounding box upper left and lower right's x,y coordinate. We don't have object bounding box coordinate because all of them are zeros.
COCO_Verb_Id_1,	COCO_Verb_Id_2,	COCO_Verb_Id_3: V-COCO's verb ID.
HICO_Verb_Id_1,	HICO_Verb_Id_2,	HICO_Verb_Id_3: HICO-DET's verb ID.
HOI_MO_Id: number 1 to number 6.
HOI_MO_Name: occlusion, truncation, transparency, gray image, rare type, small scale.

============================================================================================================
To make Mixed-V-COCO and Mixed-HICO-DET, we merge the original V-COCO and HICO-DET with V-COCO-MO and HICO-DET-MO.
The link for the original V-COCO is posted below.
https://github.com/s-gupta/v-coco

The link for the original HICO-DET is posted below.
http://www-personal.umich.edu/~ywchao/hico/

V-COCO-MO and HICO-DET-MO don't have the object bounding boxes coordinate.
Please fill all of the object bounding boxes as zeros while you merge V-COCO-MO and HICO-DET-MO with original V-COCO and HICO-DET.
