# More Lenses

## 소개
해당 모드는 게임 내 렌즈의 종류를 추가하여 문명의 관리 및 게임 편의성을 대폭 향상시켜줍니다. 현재 9개의 새로운 렌즈가 있으나 새로운 기능을 제안하신다면 추가해 드릴 수 있습니다.

## 새로운 렌즈 목록

#### 건설자 렌즈
건설자 렌즈는 개발 가능한 지원, 언덕 및 수확 가능한 타일들을 하이라이트 합니다. 이 렌즈는 건설자 유닛을 선택하면 자동으로 적용됩니다. (파일 개조로 비활성화할 수 있습니다. FAQ 참조)

![Imgur](http://i.imgur.com/6ayAc9V.jpg)
___
#### 고고학자 렌즈:
고고학자 렌즈는 유물과 난파선을 하이라이트 합니다. 지도에서 유물을 찾아 헤맬 필요가 없어집니다. 고고학자 유닛을 선택하면 자동으로 적용됩니다. (파일 개조로 비활성화할 수 있습니다. FAQ 참조)

![Imgur](http://i.imgur.com/Fe0UYRF.jpg)
___
#### 도시 오버랩 렌즈:
해당 타일이 몇 개의 도시와 겹치는지 색상으로 표시합니다. 범위는 6타일에서 9타일이며 해당 렌즈는 최대 수의 도시가 겹치는 최적의 지점을 찾아 특수 지구 또는 불가사의 건설에 최대 인접 보너스를 챙길 수 있도록 도와줍니다.

![Imgur](http://i.imgur.com/TnLHfG3.jpg)
___
#### 야만인 렌즈:
야만인 렌즈는 지도의 야만인 주둔지를 하이라이트 합니다.

![Imgur](http://i.imgur.com/V0GXjP2.jpg)
___
#### 자원 렌즈:
자원 렌즈는 지도의 자원들을 카테고리(보너스 자원, 전략 자원, 사치 자원)에 따라 하이라이트 합니다. 또한 개발 여부를 색상으로 나타냅니다.

![Imgur](http://i.imgur.com/VO36PR1.jpg)
___
#### 경관 렌즈:
경관 렌즈는 자연 경관 또는 플레이어가 건설한 불가사의를 하이라이트 합니다.

![Imgur](http://i.imgur.com/FvMyNAH.jpg)
___
#### 인접 보너스 렌즈:
문명 6 심시티의 핵심은 도시와 특수 지구의 건설 위치에 있습니다. 해당 렌즈는 다양한 인접 보너스를 색상표로 표시하여 심시티를 원활하게 해줍니다.

![Imgur](http://i.imgur.com/myYKklk.jpg)
___
#### 정찰병 렌즈:
정찰병 렌즈는 지도 상의 부족 마을들을 하이라이트 합니다. 정찰병 또는 정찰병 계열 유닛들을 선택하면 자동으로 적용됩니다. (파일 개조로 비활성화할 수 있습니다. FAQ 참조)

![Imgur](http://i.imgur.com/TnnErfb.jpg)
___

## 설치
만약 [Chao's QUI](https://github.com/chaorace/cqui) 모드를 사용하소 있다면 다음 절차를 따르십시오:

1. 모드를 여기서 다운받으세요. [here](https://www.dropbox.com/s/sd48t2g0j0g2b33/More%20Lenses%20-%20CQUI.zip?dl=0)
2. **MinimapPanel.lua**와 **MinimapPanel.xml** 파일을 CQUI 모드에서 지우십시오. 이 두 개의 파일들은 More Lenses와 충돌합니다.
3. 아래 절차를 따르면 CQUI와 More Lenses를 함께 사용할 수 있습니다.

모드 다운로드 후 다음 절차를 따르십시오:

1. 모드 폴더에 다운로드 받은 파일을 압축 해제하십시오. 기본 경로는 다음과 같습니다. *Documents\My Games\Sid Meier's Civilization VI\Mods*
2. 문명 6의 *Additional Content* 탭에서 모드를 활성화 하십시오.

## 문제 해결
모드 작동에 문제가 발생한다면 다음 절차를 시도해 보십시오:

1. 모드 설치를 DLC 폴더 내에 하십시오. 이 폴더는 문명 6를 설치한 폴더 안에 있습니다. 기본 스팀 설치 시 경로는 다음과 같습니다: *C:\Program Files (x86)\Steam\steamapps\common\Sid Meier's Civilization VI\DLC*
2. 캐시를 삭제하십시오. 기본 경로는 다음과 같습니다: *Documents\My Games\Sid Meier's Civilization VI\Cache*
3. 해당 글을 참조하십시오. [스레드](https://forums.civfanatics.com/threads/mods-not-working-at-all-help.606288/)
4. 상기에 표기한 모든 절차가 문제를 해결해주지 않는다면 이 레포지토리 또는 [여기](https://forums.civfanatics.com/threads/more-lenses.606150/)를 통해 저에게 알려주십시오.

## FAQ
##### 어떻게 렌즈를 추가를 구현했나요?
>임의로 렌즈를 추가하는 기능이 문명 6에는 내장되어 있지 않습니다. 따라서 저는 게임이 매력도 렌즈를 개조하여 강조 표시되는 타일에 대한 로직을 변경함으로서 해결했습니다.

##### 표시되는 색상을 임의로 변경할 수 있나요?
>색상표는 다음 파일에서 볼 수 있습니다: **MoreLenses_Colors.sql**. 단 게임 내 지도에서 표시되는 색상은 의도한 색상과는 다르게 보일 것입니다. 렌즈가 적용되는 타일의 배경은 일반적으로 녹색 또는 파란색 색상을 띄는 타일일 것이기 때문입니다. 이는 파란색이 보라색으로 보이는 문제 및 다른 여러 문제를 야기하며 따라서 제가 구별 가능한 8가지 색상으로 그라데이션을 구성한 이유입니다.

##### 건설자 렌즈, 고고학자 렌즈, 정찰병 렌즈와 같이 자동 적용되는 렌즈를 비활성화할 수 있나요?
>MinimapPanel.lua 파일의 상단 부분에서 다음 코드를 찾을 수 있을 것입니다:
> ```lua
> local AUTO_APPLY_BUILDER_LENS:boolean = true
> local AUTO_APPLY_ARCHEOLOGIST_LENS:boolean = true
> local AUTO_APPLY_SCOUT_LENS:boolean = true
> ```
>
>각각의 변수들을 **false** 값으로 변경하십시오.

## Credits

* @ZhouYzzz for providing the Chinese localization in #161-CQUI
* @deggesim (Simone1974 on Civfanatics) for providing the Italian localization in #250-CQUI
* @e1ectron for providing the Russian localization in #251-CQUI
* @sejbr for providing the Polish localization in #253-CQUI
* @frytom for providing the German localization in #283-CQUI
* @lctrs for providing a partial French localization in #273-CQUI
* @wbqd for providing a Korean translation in #309-CQUI
* @rzucareli for providing a Brazilian-Portuguese localization
