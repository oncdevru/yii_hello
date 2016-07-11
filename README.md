"# yii_hello" 
"# yii_hello" 

// SiteController changes and location

    public function actionSay($target = 'World')
    {
        return $this->render('say', ['target' => $target]);
    } 

// \controllers\SiteController.php

//  location of say action!!!
\views\site\say.php  
