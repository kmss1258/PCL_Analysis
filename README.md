# PCL_분석    

PCL Visualizer 시점 변경 관련
----------    
### pcl::visualization::Camera 객체 내 데이터 분석    
- focal : view Direction을 의미    
-- 물체가 놓여질 중심 지점    
- fovy : view의 Angle. Field of View in y axis의 약자로, y축으로 볼 수 있는 시야각을 의미 (라디안)    
- pos : Camera (눈 위치)의 위치    
- view : 카메라의 업벡터.    
-- 업벡터? : 좌/우 벡터를 구하기 위한 벡터. 업벡터 x X축 기저벡터 (1, 0, 0) = 우벡터, X축 기저벡터 x 업벡터 = 좌벡터    
- clip : 클리핑 평면의 깊이, clip\[0]은 가까운거 clip\[1]은 먼거
