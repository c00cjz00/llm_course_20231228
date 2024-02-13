# llm_course_20231228

## nohup
```
CUDA_VISIBLE_DEVICES=3 HF_TOKEN='hf_' python src/train_bash.py \
    --stage sft \
    --do_train True \
    >> ./mistral-alpaca_med_cqa_en.log 2>&1 &
```
