## Lab9  黑帽駭客? VPN?
### Lab9-1.1 黑帽駭客重要知識的理解
問題：

1. **什麼是黑帽駭客？**
2. **黑帽駭客與白帽駭客有何不同？**
3. **黑帽駭客的目標是什麼？**
4. **黑帽駭客可能使用的攻擊技術有哪些？**
5. **黑帽駭客的行為是否合法？**

參考答案：

1. 黑帽駭客指的是以非法或惡意方式入侵系統或網路的人。
2. 黑帽駭客與白帽駭客的區別在於動機和方法。黑帽駭客追求個人利益或惡意目的，而白帽駭客則是以維護系統安全和測試弱點為目的。
3. 黑帽駭客的目標可以是竊取敏感資訊、破壞系統運作、勒索等。
4. 黑帽駭客可能使用的攻擊技術包括惡意軟體、社交工程、網路釣魚、破解密碼等。
5. 黑帽駭客的行為是非法的，違反了法律和道德準則。

### Lab9-1.2 各種威脅防禦衡量方式與控制做法
問題：

1. **什麼是威脅防禦衡量方式？**
2. **列舉幾種常見的威脅防禦衡量方式。**
3. **什麼是防火牆？它如何幫助保護系統安全？**
4. **談談反病毒軟體的作用和功能。**
5. **什麼是入侵檢測系統（IDS）？它如何檢測和阻止入侵？**

參考答案：

1. **威脅防禦衡量方式**是指為了保護系統免受威脅而採取的措施和方法。
2. 常見的**威脅防禦衡量方式**包括但不限於以下幾種：
    1. 防火牆：使用防火牆來監控和控制網路流量，限制未經授權的訪問和攻擊。
    2. 入侵偵測系統（IDS）和入侵防禦系統（IPS）：通過監測網路流量和系統活動，識別並阻止潛在的入侵和攻擊。
    3. 強化身份驗證：使用多因素身份驗證（如密碼加上生物識別）來確保只有合法用戶可以訪問系統。
    4. 加密通訊：使用加密技術來保護敏感資訊在傳輸過程中的安全性，防止被未授權的人士截取和讀取。
    5. 定期更新和補丁管理：確保系統和應用程式都安裝最新的安全補丁和更新，以修復已知的漏洞和弱點。
    
    這些威脅防禦衡量方式有助於保護系統免受惡意攻擊和未授權訪問。通過結合不同的防禦措施，組織可以建立一個堅固的安全基礎，減少潛在的風險和威脅。同時，定期審查和更新防禦策略是必要的，以應對不斷變化的威脅環境。
    
3. **防火牆**是一種位於網路連接點的安全設備或軟體，用於監控和控制網路流量。它根據預先定義的規則和策略，過濾和阻擋未經授權的訪問和惡意網路流量。防火牆可以幫助保護系統免受入侵、網路攻擊和未經授權的訪問。
    
    防火牆的主要功能包括：
    
    - 封鎖不受信任的外部網路訪問：防火牆可以根據預定義的規則，阻擋來自不受信任的網路或IP地址的訪問，以保護內部系統免受外部攻擊。
    - 監控網路流量：防火牆可以檢視網路流量，識別和監控不尋常的網路活動，以及潛在的入侵和攻擊。
    - 實施安全策略：防火牆可以設定規則和策略，控制網路連接和通訊，以確保只有授權的用戶和服務可以訪問系統。
    - 日誌記錄和報警：防火牆可以記錄和監控網路活動，並生成日誌報告和警報，以便及時發現和應對潛在的安全事件。
4. **防毒軟體**是一種專門用於檢測、阻止和刪除電腦病毒和其他惡意軟體的程式。它具有以下功能和作用：
    - 病毒掃描：反病毒軟體可以對電腦系統進行全面的病毒掃描，檢測和識別潛在的病毒和惡意軟體。
    - 即時保護：反病毒軟體可以在實時中監控系統活動，阻止和隔離病毒和惡意軟體的執行，以保護系統免受感染。
    - 病毒定義更新：反病毒軟體會定期更新病毒定義庫，以擁有最新的病毒識別能力，可以檢測並識別最新的病毒和惡意軟體變體。
    - 威脅清除和隔離：反病毒軟體可以清除或隔離檢測到的病毒和惡意軟體，以防止它們對系統造成進一步的損害。
    - 阻止惡意連結和附件：反病毒軟體可以檢測和阻止電子郵件、網站和下載中的惡意連結和附件，以避免用戶受到釣魚攻擊和惡意軟體的感染。
5. **入侵檢測系統（Intrusion Detection System, IDS）**是一種監控網路流量和系統活動的安全技術。它的主要功能是檢測和報警可能的入侵和攻擊行為，並採取相應的措施以阻止或應對這些威脅。
 入侵檢測系統的工作方式：

- 網路監控：IDS通過監控網路流量和數據包來檢測異常的活動，例如不正常的連接、嘗試攻擊的網路流量等。
- 異常檢測：IDS使用預定義的規則和模型，比對網路流量和系統活動，識別潛在的入侵和攻擊行為，例如端口掃描、惡意代碼執行等。
- 威脅報警：當IDS檢測到可疑的活動時，它會生成警報，通知安全團隊或系統管理員進行相應的應對措施。
- 日誌記錄和報告：IDS會記錄檢測到的事件和活動，生成相關的日誌記錄和報告，用於安全審計和威脅分析。

## Lab9-2 什麼是VPN (Virtual Private Networks)？ VPN 如何幫助我們？什麼是 VPN？ VPN 如何幫助我們？
##### 使用openVpn 前
![image](https://github.com/MinChunXie/Safe-int/assets/100060507/5c18b641-a37c-47d9-8bf8-681c2ac64bdd)
##### 使用後
![image](https://github.com/MinChunXie/Safe-int/assets/100060507/34730b8e-a289-402e-9fea-d6efbaa36042)

