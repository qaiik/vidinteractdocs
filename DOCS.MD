Install pvn / pyvidnteract:\
`$ pip install pyvidnteract` OR `$ python -m pip install pyvidnteract`
\
\
\
Example one:
```python
import VidInteract

vid = VidInteract.segment('my_video_file.mp4')
range1 = VidInteract.segmentRangeOffSet(vid, 0, 3) #first three frames (offset vals)
range2 = VidInteract.segmentRangeMS(vid, 0, 1000) #first second only (first 1000 ms)

VidInteract.vidToFolder(range1, 'frames') #export frames to folder (bgr 4 some reason)
```







