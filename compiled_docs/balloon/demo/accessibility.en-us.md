{"title":"Addon","meta":{"title":"Addon","description":"\n","order":"7"},"codes":{"jsx":"\nimport { Button, Balloon, Input } from '@alifd/next';\nimport moment from 'moment';\n\nconst innerButton = <Button className=\"btrigger\">Fill in form</Button>;\n\nconst App = () => (\n    <div className=\"container nested\">\n        <Balloon id=\"inner-a11y-balloon-1\" autoFocus trigger={<Button type=\"primary\">Fill in sub-form</Button>} popupContainer={(trigger) => trigger.parentNode} triggerType=\"click\">\n            please input your age:\n            <Input placeholder=\"Age\" size=\"small\" label=\"Age :\" id=\"balloon-input-1\" /><br /><br />\n        </Balloon>\n        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\n\n        <Balloon id=\"a11y-balloon\" type=\"primary\" autoFocus trigger={innerButton} triggerType=\"click\">\n            <Balloon id=\"inner-a11y-balloon\" autoFocus trigger={<Button type=\"primary\">Fill in sub-form</Button>} popupContainer={(trigger) => trigger.parentNode} triggerType=\"click\">\n                please input your age:\n                <Input placeholder=\"Age\" size=\"small\" label=\"Age :\" id=\"balloon-input-2\" /><br /><br />\n            </Balloon>\n            <br />\n            please input your name:\n            <Input placeholder=\"Name\" size=\"small\" label=\"Name :\" id=\"balloon-input-3\" /><br /><br />\n        </Balloon>\n    </div>\n);\n\nReactDOM.render(<App />, mountNode);\n","css":"\n.container.nested {\n    margin-left: 100px;\n    margin-bottom: 50px;\n}\n\n"},"body":"\n````jsx\n\nimport { Button, Balloon, Input } from '@alifd/next';\nimport moment from 'moment';\n\nconst innerButton = <Button className=\"btrigger\">Fill in form</Button>;\n\nconst App = () => (\n    <div className=\"container nested\">\n        <Balloon id=\"inner-a11y-balloon-1\" autoFocus trigger={<Button type=\"primary\">Fill in sub-form</Button>} popupContainer={(trigger) => trigger.parentNode} triggerType=\"click\">\n            please input your age:\n            <Input placeholder=\"Age\" size=\"small\" label=\"Age :\" id=\"balloon-input-1\" /><br /><br />\n        </Balloon>\n        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\n\n        <Balloon id=\"a11y-balloon\" type=\"primary\" autoFocus trigger={innerButton} triggerType=\"click\">\n            <Balloon id=\"inner-a11y-balloon\" autoFocus trigger={<Button type=\"primary\">Fill in sub-form</Button>} popupContainer={(trigger) => trigger.parentNode} triggerType=\"click\">\n                please input your age:\n                <Input placeholder=\"Age\" size=\"small\" label=\"Age :\" id=\"balloon-input-2\" /><br /><br />\n            </Balloon>\n            <br />\n            please input your name:\n            <Input placeholder=\"Name\" size=\"small\" label=\"Name :\" id=\"balloon-input-3\" /><br /><br />\n        </Balloon>\n    </div>\n);\n\nReactDOM.render(<App />, mountNode);\n````\n\n```css\n\n.container.nested {\n    margin-left: 100px;\n    margin-bottom: 50px;\n}\n\n```","html":"<script>(function(){'use strict';\n\nvar _next = require('@alifd/next');\n\nvar _moment = require('moment');\n\nvar _moment2 = _interopRequireDefault(_moment);\n\nfunction _interopRequireDefault(obj) { return obj && obj.__esModule ? obj : { default: obj }; }\n\nvar innerButton = React.createElement(\n    _next.Button,\n    { className: 'btrigger' },\n    'Fill in form'\n);\n\nvar App = function App() {\n    return React.createElement(\n        'div',\n        { className: 'container nested' },\n        React.createElement(\n            _next.Balloon,\n            { id: 'inner-a11y-balloon-1', autoFocus: true, trigger: React.createElement(\n                    _next.Button,\n                    { type: 'primary' },\n                    'Fill in sub-form'\n                ), popupContainer: function popupContainer(trigger) {\n                    return trigger.parentNode;\n                }, triggerType: 'click' },\n            'please input your age:',\n            React.createElement(_next.Input, { placeholder: 'Age', size: 'small', label: 'Age :', id: 'balloon-input-1' }),\n            React.createElement('br', null),\n            React.createElement('br', null)\n        ),\n        '\\xA0\\xA0\\xA0\\xA0\\xA0\\xA0\\xA0\\xA0',\n        React.createElement(\n            _next.Balloon,\n            { id: 'a11y-balloon', type: 'primary', autoFocus: true, trigger: innerButton, triggerType: 'click' },\n            React.createElement(\n                _next.Balloon,\n                { id: 'inner-a11y-balloon', autoFocus: true, trigger: React.createElement(\n                        _next.Button,\n                        { type: 'primary' },\n                        'Fill in sub-form'\n                    ), popupContainer: function popupContainer(trigger) {\n                        return trigger.parentNode;\n                    }, triggerType: 'click' },\n                'please input your age:',\n                React.createElement(_next.Input, { placeholder: 'Age', size: 'small', label: 'Age :', id: 'balloon-input-2' }),\n                React.createElement('br', null),\n                React.createElement('br', null)\n            ),\n            React.createElement('br', null),\n            'please input your name:',\n            React.createElement(_next.Input, { placeholder: 'Name', size: 'small', label: 'Name :', id: 'balloon-input-3' }),\n            React.createElement('br', null),\n            React.createElement('br', null)\n        )\n    );\n};\n\nReactDOM.render(React.createElement(App, null), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\">\n<span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Button<span class=\"token punctuation\">,</span> Balloon<span class=\"token punctuation\">,</span> Input <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n<span class=\"token keyword\">import</span> moment <span class=\"token keyword\">from</span> <span class=\"token string\">'moment'</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> innerButton <span class=\"token operator\">=</span> <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>btrigger<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Fill in form</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">App</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">(</span>\n    <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>container nested<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Balloon</span></span> <span class=\"token attr-name\">id</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>inner-a11y-balloon-1<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">autoFocus</span> <span class=\"token attr-name\">trigger</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>primary<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Fill in sub-form</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">popupContainer</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">(</span><span class=\"token parameter\">trigger</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> trigger<span class=\"token punctuation\">.</span>parentNode<span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">triggerType</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>click<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            please input your age:\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Input</span></span> <span class=\"token attr-name\">placeholder</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Age<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">size</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>small<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Age :<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">id</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>balloon-input-1<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Balloon</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        &amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;\n\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Balloon</span></span> <span class=\"token attr-name\">id</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>a11y-balloon<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>primary<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">autoFocus</span> <span class=\"token attr-name\">trigger</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>innerButton<span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">triggerType</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>click<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Balloon</span></span> <span class=\"token attr-name\">id</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>inner-a11y-balloon<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">autoFocus</span> <span class=\"token attr-name\">trigger</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>primary<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Fill in sub-form</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">popupContainer</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">(</span><span class=\"token parameter\">trigger</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> trigger<span class=\"token punctuation\">.</span>parentNode<span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">triggerType</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>click<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                please input your age:\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Input</span></span> <span class=\"token attr-name\">placeholder</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Age<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">size</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>small<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Age :<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">id</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>balloon-input-2<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Balloon</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n            please input your name:\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Input</span></span> <span class=\"token attr-name\">placeholder</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Name<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">size</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>small<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Name :<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">id</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>balloon-input-3<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Balloon</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span>\n<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">App</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div><style type=\"text/css\">\n.container.nested {\n    margin-left: 100px;\n    margin-bottom: 50px;\n}\n</style><div class=\"highlight\"><pre class=\"language-css\"><code class=\"language-css\">\n<span class=\"token selector\">.container.nested</span> <span class=\"token punctuation\">{</span>\n    <span class=\"token property\">margin-left</span><span class=\"token punctuation\">:</span> 100px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">margin-bottom</span><span class=\"token punctuation\">:</span> 50px<span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span>\n</code></pre></div>"}