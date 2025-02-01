#brewFile 생성 (새로 생성)
touch Brewfile

#brewFile 생성 (Mac에 설치된 항목들을 BrewFile로 저장한 채로 )
brew bundle dump

#brewFile 덮어쓰기
brew bundle -f dump

#brewFile 확인
cat Brewfile

brew bundle
