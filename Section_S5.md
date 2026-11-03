# Section S5. Clause-level Metrics among 10 Scenarios

## 5.1 Cross-LLM Section Agreement (All Scenarios)

| Scenario | Section | BERTScore_F1 | ROUGE_L | Jaccard_clause |
|---|---|---|---|---|
| D01 | spirit_philosophy | 0.878 | 0.256 | N/A |
|  | gcc_position | 0.888 | 0.416 | 0.821 |
|  | nec_position | 0.896 | 0.460 | 0.766 |
|  | behavioural_implications | 0.864 | 0.228 | N/A |
|  | gcc_lessons_narrative | 0.864 | 0.242 | N/A |
|  | hk_specific_notes | 0.892 | 0.464 | N/A |
| D02 | spirit_philosophy | 0.876 | 0.282 | N/A |
|  | gcc_position | 0.896 | 0.439 | 0.840 |
|  | nec_position | 0.898 | 0.431 | 0.741 |
|  | behavioural_implications | 0.859 | 0.224 | N/A |
|  | gcc_lessons_narrative | 0.862 | 0.218 | N/A |
|  | hk_specific_notes | 0.899 | 0.510 | N/A |
| D03 | spirit_philosophy | 0.884 | 0.306 | N/A |
|  | gcc_position | 0.895 | 0.434 | 0.813 |
|  | nec_position | 0.900 | 0.505 | 0.740 |
|  | behavioural_implications | 0.859 | 0.226 | N/A |
|  | gcc_lessons_narrative | 0.861 | 0.204 | N/A |
|  | hk_specific_notes | 0.907 | 0.533 | N/A |
| D04 | spirit_philosophy | 0.863 | 0.249 | N/A |
|  | gcc_position | 0.890 | 0.431 | 0.786 |
|  | nec_position | 0.894 | 0.486 | 0.874 |
|  | behavioural_implications | 0.865 | 0.226 | N/A |
|  | gcc_lessons_narrative | 0.865 | 0.225 | N/A |
|  | hk_specific_notes | 0.910 | 0.576 | N/A |
| D05 | spirit_philosophy | 0.873 | 0.278 | N/A |
|  | gcc_position | 0.893 | 0.486 | 0.933 |
|  | nec_position | 0.900 | 0.505 | 0.771 |
|  | behavioural_implications | 0.872 | 0.276 | N/A |
|  | gcc_lessons_narrative | 0.865 | 0.216 | N/A |
|  | hk_specific_notes | 0.886 | 0.481 | N/A |
| D06 | spirit_philosophy | 0.878 | 0.268 | N/A |
|  | gcc_position | 0.897 | 0.460 | 0.857 |
|  | nec_position | 0.897 | 0.488 | 0.867 |
|  | behavioural_implications | 0.859 | 0.230 | N/A |
|  | gcc_lessons_narrative | 0.870 | 0.230 | N/A |
|  | hk_specific_notes | 0.895 | 0.499 | N/A |
| D07 | spirit_philosophy | 0.871 | 0.247 | N/A |
|  | gcc_position | 0.891 | 0.486 | 0.741 |
|  | nec_position | 0.898 | 0.446 | 0.667 |
|  | behavioural_implications | 0.859 | 0.232 | N/A |
|  | gcc_lessons_narrative | 0.859 | 0.217 | N/A |
|  | hk_specific_notes | 0.907 | 0.600 | N/A |
| D08 | spirit_philosophy | 0.874 | 0.272 | N/A |
|  | gcc_position | 0.895 | 0.437 | 0.863 |
|  | nec_position | 0.893 | 0.468 | 0.766 |
|  | behavioural_implications | 0.850 | 0.203 | N/A |
|  | gcc_lessons_narrative | 0.861 | 0.233 | N/A |
|  | hk_specific_notes | 0.902 | 0.483 | N/A |
| D09 | spirit_philosophy | 0.867 | 0.241 | N/A |
|  | gcc_position | 0.886 | 0.445 | 0.757 |
|  | nec_position | 0.894 | 0.478 | 0.734 |
|  | behavioural_implications | 0.852 | 0.187 | N/A |
|  | gcc_lessons_narrative | 0.855 | 0.200 | N/A |
|  | hk_specific_notes | 0.897 | 0.502 | N/A |
| D10 | spirit_philosophy | 0.868 | 0.227 | N/A |
|  | gcc_position | 0.882 | 0.464 | 0.855 |
|  | nec_position | 0.889 | 0.409 | 0.700 |
|  | behavioural_implications | 0.870 | 0.253 | N/A |
|  | gcc_lessons_narrative | 0.855 | 0.187 | N/A |
|  | hk_specific_notes | 0.907 | 0.548 | N/A |

## 5.2 Cross-LLM Pairwise Agreement

| Scenario | LLM Pair | BERTScore_F1 | ROUGE_L | Jaccard_clause |
|---|---|---|---|---|
| D01 | gpt55 ↔ deepseek | 0.878 | 0.341 | 0.839 |
|  | gpt55 ↔ qwen | 0.873 | 0.324 | 0.854 |
|  | gpt55 ↔ claude | 0.902 | 0.495 | 1.000 |
|  | gpt55 ↔ gpt4o | 0.875 | 0.272 | 0.628 |
|  | deepseek ↔ qwen | 0.881 | 0.361 | 0.887 |
|  | deepseek ↔ claude | 0.878 | 0.350 | 0.839 |
|  | deepseek ↔ gpt4o | 0.881 | 0.314 | 0.746 |
|  | qwen ↔ claude | 0.875 | 0.349 | 0.854 |
|  | qwen ↔ gpt4o | 0.886 | 0.343 | 0.662 |
|  | claude ↔ gpt4o | 0.874 | 0.293 | 0.628 |
| D02 | gpt55 ↔ deepseek | 0.877 | 0.327 | 0.833 |
|  | gpt55 ↔ qwen | 0.877 | 0.368 | 0.933 |
|  | gpt55 ↔ claude | 0.896 | 0.479 | 0.933 |
|  | gpt55 ↔ gpt4o | 0.873 | 0.276 | 0.600 |
|  | deepseek ↔ qwen | 0.883 | 0.358 | 0.885 |
|  | deepseek ↔ claude | 0.880 | 0.347 | 0.885 |
|  | deepseek ↔ gpt4o | 0.877 | 0.301 | 0.664 |
|  | qwen ↔ claude | 0.891 | 0.419 | 1.000 |
|  | qwen ↔ gpt4o | 0.886 | 0.340 | 0.586 |
|  | claude ↔ gpt4o | 0.876 | 0.293 | 0.586 |
| D03 | gpt55 ↔ deepseek | 0.883 | 0.389 | 0.846 |
|  | gpt55 ↔ qwen | 0.883 | 0.373 | 0.846 |
|  | gpt55 ↔ claude | 0.895 | 0.487 | 0.923 |
|  | gpt55 ↔ gpt4o | 0.867 | 0.239 | 0.536 |
|  | deepseek ↔ qwen | 0.891 | 0.426 | 0.900 |
|  | deepseek ↔ claude | 0.893 | 0.448 | 0.909 |
|  | deepseek ↔ gpt4o | 0.879 | 0.299 | 0.656 |
|  | qwen ↔ claude | 0.899 | 0.453 | 0.909 |
|  | qwen ↔ gpt4o | 0.882 | 0.307 | 0.656 |
|  | claude ↔ gpt4o | 0.872 | 0.259 | 0.585 |
| D04 | gpt55 ↔ deepseek | 0.870 | 0.376 | 0.923 |
|  | gpt55 ↔ qwen | 0.885 | 0.412 | 0.926 |
|  | gpt55 ↔ claude | 0.889 | 0.443 | 0.895 |
|  | gpt55 ↔ gpt4o | 0.867 | 0.249 | 0.738 |
|  | deepseek ↔ qwen | 0.885 | 0.389 | 0.852 |
|  | deepseek ↔ claude | 0.882 | 0.421 | 0.887 |
|  | deepseek ↔ gpt4o | 0.869 | 0.266 | 0.801 |
|  | qwen ↔ claude | 0.899 | 0.460 | 0.900 |
|  | qwen ↔ gpt4o | 0.891 | 0.351 | 0.670 |
|  | claude ↔ gpt4o | 0.874 | 0.288 | 0.706 |
| D05 | gpt55 ↔ deepseek | 0.876 | 0.385 | 0.883 |
|  | gpt55 ↔ qwen | 0.884 | 0.430 | 0.850 |
|  | gpt55 ↔ claude | 0.903 | 0.552 | 0.917 |
|  | gpt55 ↔ gpt4o | 0.872 | 0.274 | 0.717 |
|  | deepseek ↔ qwen | 0.880 | 0.366 | 0.900 |
|  | deepseek ↔ claude | 0.880 | 0.420 | 0.967 |
|  | deepseek ↔ gpt4o | 0.868 | 0.270 | 0.822 |
|  | qwen ↔ claude | 0.893 | 0.462 | 0.933 |
|  | qwen ↔ gpt4o | 0.883 | 0.292 | 0.733 |
|  | claude ↔ gpt4o | 0.876 | 0.287 | 0.800 |
| D06 | gpt55 ↔ deepseek | 0.872 | 0.330 | 0.875 |
|  | gpt55 ↔ qwen | 0.882 | 0.389 | 0.917 |
|  | gpt55 ↔ claude | 0.897 | 0.472 | 0.917 |
|  | gpt55 ↔ gpt4o | 0.868 | 0.259 | 0.708 |
|  | deepseek ↔ qwen | 0.887 | 0.398 | 0.958 |
|  | deepseek ↔ claude | 0.883 | 0.388 | 0.958 |
|  | deepseek ↔ gpt4o | 0.880 | 0.308 | 0.733 |
|  | qwen ↔ claude | 0.901 | 0.478 | 1.000 |
|  | qwen ↔ gpt4o | 0.885 | 0.322 | 0.775 |
|  | claude ↔ gpt4o | 0.872 | 0.279 | 0.775 |
| D07 | gpt55 ↔ deepseek | 0.881 | 0.416 | 0.871 |
|  | gpt55 ↔ qwen | 0.887 | 0.454 | 0.866 |
|  | gpt55 ↔ claude | 0.900 | 0.502 | 0.964 |
|  | gpt55 ↔ gpt4o | 0.868 | 0.235 | 0.370 |
|  | deepseek ↔ qwen | 0.880 | 0.409 | 0.926 |
|  | deepseek ↔ claude | 0.884 | 0.448 | 0.906 |
|  | deepseek ↔ gpt4o | 0.860 | 0.222 | 0.423 |
|  | qwen ↔ claude | 0.895 | 0.491 | 0.899 |
|  | qwen ↔ gpt4o | 0.881 | 0.288 | 0.428 |
|  | claude ↔ gpt4o | 0.873 | 0.252 | 0.387 |
| D08 | gpt55 ↔ deepseek | 0.870 | 0.330 | 0.830 |
|  | gpt55 ↔ qwen | 0.884 | 0.387 | 0.862 |
|  | gpt55 ↔ claude | 0.890 | 0.429 | 0.928 |
|  | gpt55 ↔ gpt4o | 0.866 | 0.236 | 0.607 |
|  | deepseek ↔ qwen | 0.878 | 0.369 | 0.967 |
|  | deepseek ↔ claude | 0.881 | 0.400 | 0.896 |
|  | deepseek ↔ gpt4o | 0.869 | 0.273 | 0.740 |
|  | qwen ↔ claude | 0.897 | 0.476 | 0.927 |
|  | qwen ↔ gpt4o | 0.882 | 0.316 | 0.721 |
|  | claude ↔ gpt4o | 0.872 | 0.276 | 0.667 |
| D09 | gpt55 ↔ deepseek | 0.876 | 0.369 | 0.775 |
|  | gpt55 ↔ qwen | 0.871 | 0.372 | 0.875 |
|  | gpt55 ↔ claude | 0.892 | 0.485 | 0.917 |
|  | gpt55 ↔ gpt4o | 0.862 | 0.231 | 0.500 |
|  | deepseek ↔ qwen | 0.874 | 0.336 | 0.900 |
|  | deepseek ↔ claude | 0.886 | 0.416 | 0.850 |
|  | deepseek ↔ gpt4o | 0.865 | 0.263 | 0.555 |
|  | qwen ↔ claude | 0.884 | 0.405 | 0.950 |
|  | qwen ↔ gpt4o | 0.875 | 0.284 | 0.583 |
|  | claude ↔ gpt4o | 0.866 | 0.259 | 0.550 |
| D10 | gpt55 ↔ deepseek | 0.879 | 0.381 | 0.771 |
|  | gpt55 ↔ qwen | 0.886 | 0.419 | 0.947 |
|  | gpt55 ↔ claude | 0.895 | 0.488 | 0.945 |
|  | gpt55 ↔ gpt4o | 0.864 | 0.228 | 0.607 |
|  | deepseek ↔ qwen | 0.881 | 0.401 | 0.818 |
|  | deepseek ↔ claude | 0.881 | 0.409 | 0.811 |
|  | deepseek ↔ gpt4o | 0.860 | 0.244 | 0.683 |
|  | qwen ↔ claude | 0.892 | 0.438 | 0.945 |
|  | qwen ↔ gpt4o | 0.878 | 0.249 | 0.607 |
|  | claude ↔ gpt4o | 0.866 | 0.223 | 0.638 |
