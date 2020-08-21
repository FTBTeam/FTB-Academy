# 도구 만들기
첫 번째로, 아래 블록들을 만들어야 합니다.

![팅커스 모드의 제작대](item:tconstruct:tooltables 1 0)
팅커스 컨스트럭트 모드의 제작대(Crafting Station)는 바닐라 제작대처럼 쓸 수 있지만, 조합 창에서 나가도 올려놓은 아이템들이 유지됩니다. 바로 옆에 설치된 블록의 인벤토리를 볼 수 있을 뿐만 아니라, 상단 탭에 연결된 다른 팅커스 모드의 블록들도 볼 수 있습니다.
![](craftingstation.png)

![틀 제작대](item:tconstruct:tooltables 1 1)
틀 제작대(Stencil Table)에서는 빈 틀(Blank Patterns)로 도구를 만들 때 필요한 도구 부품 틀을 만들 수 있습니다. 빈 틀을 틀 제작대 왼쪽 슬롯에 놓고 왼쪽에서 원하는 패턴을 선택해 만들 수 있습니다.
![](stencils.png)

![틀 상자](item:tconstruct:tooltables 1 4)
틀들을 틀 상자(Pattern Chest)에 보관할 수 있습니다.
![](patternchest.png)

![부품 제작대](item:tconstruct:tooltables 1 2)
부품 제작대(Part Builder)에서는 틀과 재료로 도구 부품을 만들 수 있습니다.
![](partbuilder.png)
왼쪽 버튼을 눌러 틀을 선택하고, 재료를 옆에 있는 두 슬롯중 하나에 넣으세요. 우측 정보창에서 넣은 재료에 대한 능력치들을 보여줍니다. 능력치에 커서를 올리면 해당 능력치에 대한 더 자세한 설명을 볼 수 있습니다.
![](buildingpart.png)
또한 부품 제작대에서는 금속이 아닌 재료들만 부품으로 만들 수 있습니다. 금속 부품을 만드려면 나중에 다룰 용광로가 필요합니다.
![](metalpart.png)
만약 부품 제작대 옆에 틀 상자를 붙여 설치하고, 팅커스 모드의 제작대와 연결되어있다면, 틀을 따로 꺼내서 가져올 필요 없이 바로 왼쪽에서 선택해 사용할 수 있습니다.

![도구 조립대](item:tconstruct:tooltables 1 3)
도구 조립대(Tool Station)에서는 부품을 조립해 도구를 만듭니다.
![](toolstation.png)
만들고싶은 도구를 왼쪽에서 선택한 후, 부품을 알맞은 슬롯에 올리세요.
우측 정보창에는 사용한 부품의 재료에 따른 능력치와 특성을 알려줍니다.

아래 사진의 곡괭이(돌 곡괭이 머리, 종이 조임쇠, 스펀지 도구 막대로 만든)는 철 광석과 그보다 더 무른, 석탄 광석이나 돌 같은 블록들을 캘 수 있습니다. 당연히 다이아몬드나 레드스톤 광석 등을 캘 수 는 없습니다.
우상단 텍스트 상자에 글자를 적어 도구에 이름을 붙일 수 있습니다.
![](buildingtool.png)
도구 조립대 중앙에 완성된 도구를 놓고 주변에 모디파이어 아이템을 놓아 모디파이어(modifier, 팅커스 도구의 업그레이드)를 적용시킬 수 있습니다.
재료의 정석 책에서 도구에 적용시킬 수 있는 모디파이어들을 확인하세요.
도구에는 한정된 개수의 모디파이어만을 적용시킬 수 있습니다. 도구 조립대에 도구를 올려놓아 우측 정보창에서 남은 모디파이어 슬롯을 알 수 있습니다.
![](modifiers.png)

![도구 조립소](item:tconstruct:toolforge)
도구 조립대에서는 한정된 도구만 제작할 수 있습니다. 다른 모든 도구들을 만드려면 도구 조립소(Tool Forge)가 필요합니다. 도구 조립대와 비슷하게 사용할 수 있지만, 추가적으로 조립대에서는 만들지 못했던 도구들도 만들 수 있습니다. 도구 조립소는 어떤 금속 블록으로도 만들 수 있으며, 텍스쳐 이외에 성능은 모두 동일합니다.
![](toolforge.png)

도구에 커서를 올리면 능력치와 모디파이어, 도구 레벨들을 볼 수 있습니다. Tinkers' Tool Leveling 모드가 설치되어 있다면(이 모드팩에도 있습니다), 도구를 사용할수록 도구 경험치가 오릅니다. 도구 레벨이 오리면 추가적인 모디파이어 슬롯을 얻을 수 있습니다!
![](toolxp.png)

완전히 수리된 도구와 원하는 도구 부품을 합치는 방식으로 도구 부품을 교체할 수 있습니다. 교체당한 도구 부품과 해당 부품의 특성들은 사라집니다.
![](partswap.png)

능력치나 특성을 바꾸지 않고 채굴 등급을 업그레이드하고 싶다면, 연마 키트(Sharpening Kit)를 사용해 도구의 부품 교체 없이 채굴 등급만을 바꿀 수 있습니다. 모디파이어 슬롯을 차지하지 않을 뿐만 아니라, 여러 번 등급을 바꿀 수도 있습니다. 동일한 재료로 만들어진 도구(도구 머리만 같으면 됨)와 연마 키트를 조합하면 도구 조립대/조립소 없이도 도구의 내구도를 수리할 수 있습니다.
![](sharpeningkit.png)

엠보싱(Embossing)는 도구 부품을 교체하지 않고도 원하는 부품의 특성을 추가할 수 있습니다. 재료의 특성은 좋지만 능력치가 마음에 들지 않을 때, 도구 부품을 교체하는 대신, 도구에 엠보싱하면 됩니다!
![](embossment.png)