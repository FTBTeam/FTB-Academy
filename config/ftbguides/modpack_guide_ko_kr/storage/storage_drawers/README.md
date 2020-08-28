# 스토리지 드로워즈

스토리지 드로워즈(Storage Drawers) 모드를 이용하면 방대한 양의 단일 종류 아이템을 저장할 수 있습니다.
아이템을 들고 드로워(Drawer) 정면을 우클릭하여 저장하거나, 우클릭을 꾹 눌러 인벤토리에 있는 동일 종류의 아이템을 전부 한번에 저장할 수 있습니다. 좌클릭하면 아이템을 1개씩 꺼낼 수 있고, 웅크린채로 좌클릭하면 한 스택씩 아이템을 꺼낼 수 있습니다.

![](1x1.png)
![Basic Drawer](item:storagedrawers:basicdrawers)
Basic Drawer는 단일 종류의 아이템을 32스택(stack, 한스택당 64개)씩 저장할 수 있습니다.
![](1x2.png)
![Basic Drawers 1x2](item:storagedrawers:basicdrawers 1 1)
1x2 드로워는 각 칸마다 단일 종류의 아이템을 16스택씩 저장할 수 있습니다.
![](2x2.png)
![Basic Drawers 2x2](item:storagedrawers:basicdrawers 1 2)
2x2 드로워는 각 칸마다 단일 종류의 아이템을 8스택씩 저장할 수 있습니다.
![](half.png)
![Half Drawers 1x2](item:storagedrawers:basicdrawers 1 3)
각 드로워는 기본 버전의 절반만큼 아이템을 저장할 수 있는 반블록 버전이 존재합니다.

![](compacting.png)
![압축 서랍](item:storagedrawers:compdrawers)
압축 서랍(Compacting Drawer)은 저장된 아이템의 각 형태를 보여줍니다. 저장된 아이템을 사용해 3x3조합대를 꽉 채워 만드는 조합법과 어떤 아이템을 사용해 3x3조합대를 꽉 채워 저장된 아이템을 만드는 조합법이 존재한다면, 해당 아이템들을 보여줍니다. 예시로 철 주괴를 넣으면 철 블록과 철 조각을 보여줍니다. 이러한 기능들 덕분에 압축 서랍은 금속 종류를 저장하기 좋습니다. 저장 용량은 가장 큰 버전의 아이템을 기준으로 계산되기 떄문에, 예시로 Storage Upgrade (V)를 적용한다면 32배나 더 많은 철 블록들을 보관할 수 있습니다.

![](controller.png)
![Drawer Controller](item:storagedrawers:controller)
Drawer Controller를 사용하면 12칸 이내의 다른 연결된 모든 드로워들에 접근할 수 있습니다. 단일 드로워처럼 작동하지만 모든 연결된 드로워에 등록된 아이템을 집어넣거나, 빼낼 수 있습니다.
![](controller2.png)



![](gui.png)
빈손으로 드로워 정면을 웅크린채로 우클릭하면 저장된 아이템이나 적용된 업그레이드 등을 확인하고 관리할 수 있는 드로워 메뉴를 볼 수 있습니다.

업그레이드중에는 단순히 저장용량을 늘리는 업그레이드뿐만 아니라 드로워에 특별한 기능을 부여하는 업그레이드들도 있습니다. 각 업그레이드의 툴팁을 확인하면 어떤 기능인지를 알 수 있지만, 친절히 여기에서도 설명해 드리겠습니다.

![Storage Upgrade (I)](item:storagedrawers:upgrade_storage)
Storage Upgrade들은 기존 드로워의 용량을 배로 늘려줍니다. 더 높은 등급의 업그레이드일수록 저장용량을 더 많이 뻥튀기시켜줍니다. 특정 등급의 업그레이드를 적용시킬 때, 이전 등급의 업그레이드들을 적용시키지 않아도 됩니다. 원한다면 최고 등급 업그레이드 7개를 적용시켜 224배나 많이 저장하도록 만들수도 있습니다.
![Storage Downgrade](item:storagedrawers:upgrade\_one\_stack)
Storage Downgrade는 반대로 저장 용량을 1스택으로 만들어버립니다.
![동상 업그레이드 (I)](item:storagedrawers:upgrade_status)
동상 업그레이드(Status Upgrade)들은 드로워에 아이템이 얼마나 저장되었는지를 알려주는 바를 추가합니다. 첫 번째 등급은 드로워가 가득 찼을때만 바에 불이 들어오지만, 두 번째 등급의 업그레이드는 얼마나 찼는지에 따라 바가 점점 차오릅니다.
![Void Upgrade](item:storagedrawers:upgrade_void)
Void Upgrade는 드로워가 가득 찼을때 들어오는 아이템들을 없애버립니다. 이 업그레이드는 조약돌처럼 없어져도 되는 아이템들을 보관할 때에 좋습니다.
![Redstone Upgrade](item:storagedrawers:upgrade_redstone)
Redstone Upgrade들은 드로워에 아이템이 얼마나 들어있는지에 따라 레드스톤 신호를 내보내도록 만들어줍니다.

드로워와 함께 사용하기 좋은 다른 아이템들도 있습니다.
![](tape.png)
![Packing Tape](item:storagedrawers:tape)
기본적으로는 드로워를 부시면 안에 들어있는 내용물들이 전부 튀어나와 엄청난 난리를 치게 될겁니다. 만약 드로워에 엄청난 양의 아이템이 들어있었다면 랙이 심하게 걸릴 수 있으니 절대 추천드리지 않습니다. 드로워에 Packing Tape를 사용하면 부숴도 아이템이 튀어나오지 않습니다.
만약 포장된 드로워를 조합에 사용한다면 안에 들어있던 아이템은 전부 사라지니 주의하세요.

![](quantify.png)
![Quantify Key](item:storagedrawers:quantify_key)
Quantify Key를 드로워에 사용하면 아이템이 얼마나 저장되어 있는지를 숫자로 보여줍니다.

![](locked.png)
![Drawer Key](item:storagedrawers:drawer_key)
Drawer Key를 사용해 드로워를 잠글 수 있으며, 잠긴 드로워는 아이템을 전부 꺼내도 다른 아이템이 들어가지 않도록 보관하던 아이템들을 기억합니다.

![](personal.png)
![Personal Key](item:storagedrawers:personal_key)
Personal Key를 드로워에 사용하면 다른사람들이 드로워와 상호작용할 수 없도록 만듭니다. 하지만 파이프등의 아이템 이동 장치들은 여전히 동작합니다.

![](concealment.png)
![Concealment Key](item:storagedrawers:shroud_key)
Concealment Key를 드로워에 사용하면 저장된 아이템들을 가려 무슨 아이템이 저장됬는지를 알 수 없게 만듭니다.

키를 들고 드로워를 우클릭해 기능을 적용할 수 있으며, 키로 Drawer Controller를 우클릭하면 연결된 모든 드로워에 기능을 적용할 수도 있습니다.
