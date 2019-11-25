# Cplusplus

寫程式就像平常我烹飪一樣，要資料結構（即食譜上的材料和其克重或數量）以及 演算（即如何烹飪）。

C++ 是屬於 OOP，C 屬於程序程式重視演算法，而 C++ 因為歸屬物件導向，所以非常重視資料，在 OOP 世界，必須徹底了解基本的型別系統，方能真正了解一個語言！C++ 以 class 來描述新的資料型態，而 object 即物件，則是根據 class 計畫建構的特定資料結構。舉例來說，104 應徵履歷釋出的 job candidate 需要符合條件的角色是種類別，而面試上的應試者則是物件。

C 屬於 Top-Down，而 C++ 屬於 Bottom-Up，彼此不同之處在於，物件導向是先設計要處理事情的類別，並由類別的物件設計方程式，由低階的類別往上至高階的程式設計。

類別因為是種資料型別，所以優勢上比沒有類別的語言來說，除了 reuse 代碼外，還能隱藏資訊，保護資料，避免其被不正當存取。

類別繼承可以產生函數的多重定義 func override。（Function Overloading is when multiple function with same name exist in a class. Function Overriding is when function have same prototype in base class as well as derived class.）

BTW，其實筆者我自學 Golang，發現 Go 本身沒有類別也沒有繼承時，就覺得他的潮會在未來幾年內衰退...(個人淺見，希望諸位海涵)。

C++ v11 https://github.com/QueenieCplusplus/Cplusplus11

_____________

# 推薦書籍

  Bjarne Stroustrup, the Creator of C++ 撰寫的語法書 The C++ Programming Language
  能把觀念釐清!
  
  C++ Premier，提供實作範例
  
 _____________

# 學習 OOP 語言的建言

通透了解這門語言的所有型別

編寫程式的機制
  https://github.com/QueenieCplusplus/ProgramSchema
  
  _____________

# 學習程式語言的方法

＊ 在程式碼中表現出概念

＊ 在程式碼中表現概念之間的關係（參數、繼承、擁有權）
   https://github.com/QueenieCplusplus/Cplusplus_Abstract_Types （繼承關係）

＊ 讓簡單的事情保持簡約（讓複雜的事情切碎成很多簡單的事情，就能直接去做。）

_____________

# 維持簡單風格的方式

_____________

* Type, 檢查型別（靜態型別） 
  https://github.com/QueenieCplusplus/Type_Check
  
  _____________

* Scope, 讓資訊保留在區域範圍內（避免全域變數、避免使用指標）
  https://github.com/QueenieCplusplus/Cplusplus_Pointer
  
  _____________

* Be Practical, 具體化，避免抽象化 (避免泛型、類別階層導入、參數行為) 
  https://github.com/QueenieCplusplus/Cplusplus_Class
  
  _____________

# 本儲存庫摘要：

_____________

1. Abstract Class, 介面或是抽象類別
  https://github.com/QueenieCplusplus/Cplusplus_Abstract_Types
  
_____________
  
2. Concrete Class, 具體類別
  https://github.com/QueenieCplusplus/Cplusplus_Class
  
_____________

3. Obj, 物件觀念
  https://github.com/QueenieCplusplus/Cplusplus_Object
  
_____________
  
4. Structure, 結構型別
  https://github.com/QueenieCplusplus/Cplusplus_Structure
  
5. stuctor & destructor, 型別的建構與解構
  https://github.com/QueenieCplusplus/Cplusplus_destructor
  
_____________
  
6. Ptr & Ref, 指標與參考 ＊ & （不推薦使用）
  https://github.com/QueenieCplusplus/Cplusplus_Pointer
  
_____________
  
7. Main Thread, 主要執行緒
  https://github.com/QueenieCplusplus/1122Try
  
_____________
  
8. Type Check, 編程員良好的習慣之一：型別檢查 （函數本體檢驗輸入值的代碼...通常是體積膨脹關鍵之一）
  https://github.com/QueenieCplusplus/Type_Check
  
_____________
  
9. Polymorphism, 多型類別

   範例：
   https://github.com/QueenieCplusplus/Cplusplus_Abstract_Types/blob/master/Interface.cpp
   
_____________

10. Template, 模板 (支援泛型)
  https://github.com/QueenieCplusplus/Cplusplus_Template
  
_____________

11. Generics, 泛型 (不推薦使用)
  https://github.com/QueenieCplusplus/Cplusplus_Generics/blob/master/README.md
  
_____________

12. Pass Obj, 傳遞物件，包含 pass by value 和 pass by ref
  https://github.com/QueenieCplusplus/Cplusplus_Pass_Object
  
_____________

13. Func Overload, 運算子多載 (可以說是同名函數的各種引數型別通行證。)
 https://github.com/QueenieCplusplus/Cplusplus_Pass_Object/blob/master/README.md#ops-overload--func-overload

_____________

14. Lifecycle, 物件的生命週期 (推薦搭配作用域議題一起看。)

    https://github.com/QueenieCplusplus/Cplusplus_LifeCycle

_____________

15. PolyMorphicsm, 多型類別 （筆者認為此議題概念與運算子多載觀念相同，只是到類別階層。）

    https://github.com/QueenieCplusplus/Cplusplus_PolyMorphicsm
    
_____________

16. Naming Style, 命名風格 (風格百出，坑洞百出。請一團隊好好遵循一種風格！)

    https://github.com/QueenieCplusplus/Cplusplus_NameStyle
    
 _____________
 
 17. Initialize, 初始化的意義 (動態記憶體配置，建議使用初始化後的變數。)
 
     https://github.com/QueenieCplusplus/Cplusplus_Initialize
     
 _____________
 
 18. Scope, 作用域
 
      https://github.com/QueenieCplusplus/Cplusplus_Scope
 
 _____________    
 
 19. Keyword, 25 個關鍵字 (TBD, 待續。)
 
      https://github.com/QueenieCplusplus/Cplusplus_KeyWords/blob/master/README.md
 
 






