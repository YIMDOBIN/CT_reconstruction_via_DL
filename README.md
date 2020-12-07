# CT_reconstruction_via_DL
CT_reconstruction_via_DL

CT는 일반 X선 촬영과 비교하여 환자에게 피폭되는 선량이 수십,수백배에 달합니다.
따라서 적은 X선을 사용하면서도 고화질의 CT 영상을 획득할 수 있는 방법이 무엇이 있을까에 대해 생각해보았습니다.
결론은 만능 딥러닝이죠 ㅎㅎ
MRI(k-space to image)를 성공적으로 재구성했던 AUTOMAP을 변환하여 CT (sinogram to image)에 적용해보았습니다.
현재는 s-IGDT reconstruction via deep learning 에 도전중입니다!

An increasing use of computed tomography (CT) in modern medicine has raised radiation dose issues. 
Strategies for low-dose CT imaging are necessary in order to prevent side effects. 
Among the strategies, limited-angle CT scans are being used for reducing radiation dose. 
However, the limited angle scans cause severe artifacts in the images reconstructed by using conventional reconstruction algorithms, 
such as filtered back-projection (FBP), due to insufficient data. 
To solve this issue, various methods have been proposed to replace conventional reconstruction algorithms. 
In this code, we proposed a data-driven deep learning-based limited-angle CT reconstruction method.
