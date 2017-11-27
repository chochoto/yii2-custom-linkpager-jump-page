# yii2-widget-linkpager
![Effect picture 1](https://raw.githubusercontent.com/chochoto/yii2-widget-linkpager/master/doc/Screenshot-2017-11-27.png "Effect picture 1")  

# Usage
Copy file to common\widgets\
GridView options
```php
    <?php
        echo GridView::widget([
            'dataProvider' => $dataProvider,
            'pager' => [
                'class' => 'common\widgets\DropDownPager',
                'options'=>['class'=>'pagination'],
                'firstPageLabel' => 'First',
                'lastPageLabel'  => 'Last',
                'maxButtonCount'=>10,
                'hideOnSinglePage'=>false,
            ],
```            
