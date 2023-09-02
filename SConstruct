# autoC/SConstruct

# SCons 라이브러리 임포트
import os

# SCons 환경 설정 생성
env = Environment()

# 'ASW' 디렉터리로의 상대 경로
asw_dir = os.path.join('ASW')

# 'ASW' 디렉터리 내의 'SConscript' 파일 호출
SConscript(os.path.join(asw_dir, 'SConscript'), exports='env')
