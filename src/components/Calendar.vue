<template>
  <div id="app">
    <div class="van-overlay" style="z-index: 2001;"></div>
    <div class="van-popup van-popup--round van-popup--bottom van-calendar__popup"
         style="z-index: 2002;">
      <div class="van-calendar">
        <div class="van-calendar__header">
          <div class="van-calendar__header-title">title slot</div>
<!--          h44 + lh44px -->
          <div class="van-calendar__header-subtitle">2021年4月</div>
          <div class="van-calendar__weekdays"><span class="van-calendar__weekday">日</span><span
            class="van-calendar__weekday">一</span><span class="van-calendar__weekday">二</span><span
            class="van-calendar__weekday">三</span><span class="van-calendar__weekday">四</span><span
            class="van-calendar__weekday">五</span><span class="van-calendar__weekday">六</span></div>
        </div>
        <div class="van-calendar__body">
          <div class="van-calendar__month">
            <div role="grid" class="van-calendar__days">
              <div class="van-calendar__month-mark" style="">4</div>
              <div role="gridcell" class="van-calendar__day van-calendar__day--disabled"
                   style="margin-left: 57.1429%;">1
              </div>
              <div role="gridcell" class="van-calendar__day van-calendar__day--disabled" style="">
                2
              </div>
              <div role="gridcell" class="van-calendar__day van-calendar__day--disabled" style="">
                3
              </div>
              <div role="gridcell" class="van-calendar__day van-calendar__day--disabled" style="">
                4
              </div>
              <div role="gridcell" class="van-calendar__day van-calendar__day--disabled">5</div>
              <div role="gridcell" class="van-calendar__day van-calendar__day--disabled">6</div>
              <div role="gridcell" class="van-calendar__day van-calendar__day--disabled">7</div>
              <div role="gridcell" class="van-calendar__day van-calendar__day--disabled">8</div>
              <div role="gridcell" class="van-calendar__day van-calendar__day--disabled">9</div>
              <div role="gridcell" class="van-calendar__day van-calendar__day--disabled">10</div>
              <div role="gridcell" class="van-calendar__day van-calendar__day--disabled">11</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">
                <div class="van-calendar__selected-day">12</div>
              </div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">13</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">14</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">15</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">16</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">17</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">18</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">19</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">20</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">21</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">22</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">23</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">24</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">25</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">26</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">27</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">28</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">29</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">30</div>
            </div>
          </div>
          <div class="van-calendar__month">
            <div class="van-calendar__month-title">2021年5月</div>
            <div role="grid" class="van-calendar__days">
              <div class="van-calendar__month-mark" style="">5</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day"
                   style="margin-left: 85.7143%;">1
              </div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day" style="">2</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day" style="">3</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day" style="">4</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day" style="">5</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">6</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">7</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">8</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">9</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">10</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">11</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">12</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">13</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">14</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">15</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">16</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">17</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">18</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">19</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">20</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">21</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">22</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">23</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">24</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">25</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">26</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">27</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">28</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">29</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">30</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">31</div>
            </div>
          </div>
          <div class="van-calendar__month">
            <div class="van-calendar__month-title">2021年6月</div>
            <div role="grid" class="van-calendar__days">
              <div class="van-calendar__month-mark" style="">6</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day"
                   style="margin-left: 28.5714%;">1
              </div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day" style="">2</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day" style="">3</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day" style="">4</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">5</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">6</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">7</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">8</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">9</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">10</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">11</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">12</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">13</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">14</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">15</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">16</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">17</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">18</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">19</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">20</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">21</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">22</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">23</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">24</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">25</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">26</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">27</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">28</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">29</div>
              <div role="gridcell" tabindex="-1" class="van-calendar__day">30</div>
            </div>
          </div>
          <div class="van-calendar__month">
            <div class="van-calendar__month-title">2021年7月</div>
            <div role="grid" class="van-calendar__days">
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
            </div>
          </div>
          <div class="van-calendar__month">
            <div class="van-calendar__month-title">2021年8月</div>
            <div role="grid" class="van-calendar__days">
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
            </div>
          </div>
          <div class="van-calendar__month">
            <div class="van-calendar__month-title">2021年9月</div>
            <div role="grid" class="van-calendar__days">
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
            </div>
          </div>
          <div class="van-calendar__month">
            <div class="van-calendar__month-title">2021年10月</div>
            <div role="grid" class="van-calendar__days">
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
              <div role="gridcell" tabindex="-1"
                   class="van-calendar__day van-calendar__day--placeholder"
                   style="width: 100%;"></div>
            </div>
          </div>
        </div>
        <div class="van-calendar__footer">footer slot</div>
<!--        dib + p-->
      </div>
      <i role="button" tabindex="0"
         class="van-icon van-icon-cross van-popup__close-icon van-popup__close-icon--top-right">
        <!----></i></div>
  </div>
</template>
